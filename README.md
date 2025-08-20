# AI Health Navigator

Final project for the Building AI course

## Summary

AI Health Navigator is an AI-powered symptom checker and triage assistant. It helps patients describe symptoms, suggests possible conditions, and provides guidance on whether medical attention is needed. Goal: relieve doctors, reduce waiting times, and improve healthcare efficiency.

## Background

The healthcare system is under pressure due to:
* Shortage of doctors in many countries  
* Long waiting times for patients  
* Growing demand for quick and reliable health information  

My personal motivation is to contribute to healthcare accessibility. Many people delay seeking care or overwhelm emergency rooms with non-urgent issues. An AI assistant can serve as a first step to triage and guide people efficiently. This project matters because it can reduce pressure on healthcare systems, especially in times of crisis.

## How is it used?

* Patients interact with the AI via a mobile app or web platform.  
* They input their symptoms in plain language.  
* The AI system uses NLP (Natural Language Processing) to analyze input.  
* It returns likely conditions, advice (self-care, see a GP, emergency), and next steps.  

The main users are patients, but doctors and healthcare organizations also benefit through reduced workload and improved patient flow.

<img src="https://upload.wikimedia.org/wikipedia/commons/6/65/Hospital_icon.svg" width="150">

## Data sources and AI methods

Data sources:  
* Public medical symptom datasets (e.g., [SymCAT](https://www.symcat.com/), open health APIs)  
* Research literature and anonymized healthcare records (where legally possible)  

AI methods:  
* Natural Language Processing (for symptom input)  
* Classification models (predict likely conditions)  
* Decision trees / neural networks (triage recommendations)  

| Technique   | Use case |
| ----------- | -------- |
| NLP         | Understanding patient symptoms |
| Machine Learning | Predicting possible conditions |
| Rule-based + AI hybrid | Giving safe triage recommendations |

## Challenges

* Accuracy and safety: AI should **support**, not replace doctors.  
* Data quality: Biased or incomplete data leads to unreliable advice.  
* Ethical issues: Privacy of sensitive health data must be protected.  
* Not suitable for all conditions: Emergency cases still need direct medical attention.  

## What next?

* Build a prototype with a small medical dataset.  
* Collaborate with healthcare professionals to validate results.  
* Scale into a multilingual system to reach more communities.  
* Potential integration with telemedicine services.  

## Acknowledgments

* Inspired by global healthcare challenges and the need to relieve overburdened doctors.  
* Open datasets such as and academic research in digital health.  
* Thanks to Reaktor and University of Helsinki for the Building AI course and template.  
