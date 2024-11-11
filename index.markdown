---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<img src="{{ '/images/cover.webp' | relative_url }}" alt="Full-width image" style="width: 100vw; height: auto; display: block;">

## TAIC Workshop, Co-located with ITASEC25
Welcome to the Trustworthy AI for Cybersecurity (TAIC) workshop webpage, which hosts all the info and news needed for the workshop. 

## Important Dates 
* December 9, 2024: Deadline for Workshop Paper Submission
* January 3, 2025: Author Notification
* February 3-8, 2025: Conference (TAIC workshop day yet to be decided)  
* February 20, 2025: Camera-ready deadline

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | relative_url }}){% endif %}
{% endfor %}
</div>

# Workshop Abstract  
Artificial Intelligence (AI) has now become a well-established technology in cybersecurity applications. In this scenario, the use of AI and Machine Learning (ML) techniques aims to foster the security of existing tools by operating as a core or additional mechanism to prevent and detect threats, revolutionizing key areas such as vulnerability and malware detection. As cyber threats grow increasingly sophisticated and complex, the cybersecurity landscape demands innovative solutions. AI-driven approaches offer the automation and intelligence necessary to stay ahead of evolving attacks and novel threats, providing a crucial line of defense in our rapidly changing digital ecosystem.
However, alongside an increasing number of cyberthreats, a likewise alarming number of vulnerabilities is associated with AI techniques, raising concerns about their use. In addition, such techniques are often conceived as a “black box”, thus giving decisions whose rationale remains unclear, sometimes even incorporating undesired biases. Given the wide use of AI techniques to support decision-making in high-stakes scenarios, such as in cybersecurity applications, these issues led the research community to focus on the trustworthiness of AI techniques, with the unified goal of validating their use by increasing security, transparency and fairness. 
In light of these issues and considerations, this workshop focuses on the trustworthiness of AI techniques for cybersecurity systems. Therefore, we are interested in two specific aspects: (i) Trustworthy AI, where we focus on the trustworthiness of AI systems, thus aiming to advance the discussion on the security of models and algorithms by analyzing attack and defense techniques (e.g., evasion attacks and adversarial training, respectively), on explainability techniques increasing transparency, and finally on methods analyzing the fairness of the models and algorithms;
(ii) AI for Cybersecurity, which refers to the study and analysis of cybersecurity tasks where the use of AI can improve the overall level of security, like spam, malware, and botnet detection, as well as automatically localizing and fixing security vulnerabilities in software applications.
Through these two separate yet affine aspects, our goal is to foster a unified discussion on trustworthy AI in cybersecurity. By doing so, we aim to help mitigate these issues and prevent them from hindering the development and adoption of AI techniques.

# Workshop Organization

<div style="display: flex; flex-wrap: wrap; gap: 20px; justify-content: center;">
  <div style="display: flex; flex-direction: column; align-items: center; flex-basis: 30%;">
    <img src="{{ '/images/giorgio.jpeg' | relative_url }}" alt="Giorgio Piras" style="width: 100px; height: 100px; object-fit: cover; border-radius: 50%;">
    <p style="margin-top: 10px; text-align: center;">
      <span>Giorgio Piras</span><br>
      <span style="font-size: 0.7em; font-style: italic;">University of Cagliari</span>
    </p>
  </div>
  <div style="display: flex; flex-direction: column; align-items: center; flex-basis: 30%;">
    <img src="{{ '/images/emanuele.jpg' | relative_url }}" alt="Emanuele Iannone" style="width: 100px; height: 100px; object-fit: cover; border-radius: 50%;">
    <p style="margin-top: 10px; text-align: center;">
      <span>Emanuele Iannone</span><br>
      <span style="font-size: 0.7em; font-style: italic;">Hamburg University of Technology</span>
    </p>
  </div>
  <div style="display: flex; flex-direction: column; align-items: center; flex-basis: 30%;">
    <img src="{{ '/images/maura.jpg' | relative_url }}" alt="Maura Pintor" style="width: 100px; height: 100px; object-fit: cover; border-radius: 50%;">
    <p style="margin-top: 10px; text-align: center;">
      <span>Maura Pintor</span><br>
      <span style="font-size: 0.7em; font-style: italic;">University of Cagliari</span>
    </p>
  </div>
  <div style="display: flex; flex-direction: column; align-items: center; flex-basis: 30%;">
    <img src="{{ '/images/katja.jpeg' | relative_url }}" alt="Katja Tuma" style="width: 100px; height: 100px; object-fit: cover; object-position: 50% 10%; border-radius: 50%;">
    <p style="margin-top: 10px; text-align: center;">
      <span>Katja Tuma</span><br>
      <span style="font-size: 0.7em; font-style: italic;">Vrije Universiteit</span>
    </p>
  </div>
  <div style="display: flex; flex-direction: column; align-items: center; flex-basis: 30%;">
    <img src="{{ '/images/battista.jpeg' | relative_url }}" alt="Battista Biggio" style="width: 100px; height: 100px; object-fit: cover; border-radius: 50%;">
    <p style="margin-top: 10px; text-align: center;">
      <span>Battista Biggio</span><br>
      <span style="font-size: 0.7em; font-style: italic;">University of Cagliari</span>
    </p>
  </div>
  <div style="display: flex; flex-direction: column; align-items: center; flex-basis: 30%;">
    <img src="{{ '/images/fabio.jpg' | relative_url }}" alt="Fabio Massacci" style="width: 100px; height: 100px; object-fit: cover; border-radius: 50%;">
    <p style="margin-top: 10px; text-align: center;">
      <span>Fabio Massacci</span><br>
      <span style="font-size: 0.7em; font-style: italic;">University of Trento</span><br>
      <span style="font-size: 0.7em; font-style: italic;">Vrije Universiteit</span>
    </p>
  </div>
</div>  

### Contact 
For any question, or info, please contact Giorgio Piras at: [giorgio.piras@unica.it](mailto:giorgio.piras@unica.it)<br> 

### Sec4Ai4Sec EU Project: 
This workshop has been organized in the frame of the Sec4AI4Sec European project, that aims to create a range of cutting-edge technologies, open-source tools, and new methodologies for designing and certifying secure AI-enhanced systems and AI-enhanced systems for security. Additionally, it will provide reference benchmarks that can be utilised to standardise the evaluation of research outcomes within the secure software research community.<br>

<div style="text-align: center;">
  <img src="{{ '/images/sec4ai4sec-eu.png' | relative_url }}" alt="Centered Image" style="width: 80%; height: auto;"><br>
  <p style="margin-top: 10px;">Find out more about the Sec4Ai4Sec project in the <a href="https://www.sec4ai4sec-project.eu/" target="_blank">official webpage</a>.</p>
</div>

