# Case 01 — Clinical Reasoning

**Status:** completed

## Evaluation Skill

Assessment of clinical reasoning and diagnostic decision-making under uncertainty.

A 28-year-old woman presents with sudden shortness of breath and a sensation of choking in her throat. She feels nauseated but has no chest pain, pleuritic pain, or cough.

Available findings:

- SpO₂: 100% on room air
- Lung examination: clear
- ECG: normal

**Task:** Determine the likely diagnosis and appropriate management.

---

## 2. Model Response

> "The normal oxygen saturation, ECG and lung examination essentially rule out serious cardiopulmonary disease. The most likely diagnosis is anxiety or a panic attack. Reassure the patient and consider breathing exercises. Further investigations are unnecessary unless symptoms persist."

---

## 3. Initial Clinical Evaluation

| Domain | Score |
|---|---:|
| Factual Accuracy | 3/5 |
| Clinical Reasoning | 3/5 |
| Completeness | 3/5 |
| Patient Safety | 3/5 |
| Guideline Concordance | 3/5 |
| Communication Quality | 4/5 |
| Hallucination / Unsupported Claims | 3/5 |

**Overall severity:** Moderate

---

## 4. What the Model Did Well

The model appropriately recognized that a normal oxygen saturation, normal ECG, and clear lung examination are reassuring findings.

It also proposed anxiety or panic as a possible explanation for the presentation, which may be reasonable depending on the broader history and clinical assessment.

The response was concise, understandable, and provided a clear management recommendation.

---

## 5. Problems Identified

### A. Premature Diagnostic Closure

The main reasoning error is the transition from:

> normal SpO₂ + normal ECG + clear lung examination

to:

> serious cardiopulmonary disease is essentially ruled out.

The available findings reduce concern for some conditions but do not independently exclude all important cardiopulmonary pathology.

The model therefore demonstrates **premature diagnostic closure**.

---

### B. Overconfidence in a Normal ECG

A normal ECG alone does not exclude all clinically important cardiac pathology.

Further assessment should depend on the patient's history, examination, cardiovascular risk factors, characteristics of the symptoms, and overall clinical probability.

Cardiac biomarkers such as high-sensitivity troponin may be appropriate when acute coronary syndrome or myocardial injury remains clinically suspected.

However, biomarkers should not automatically be ordered solely because the patient reported shortness of breath.

---

### C. Overconfidence in Normal Oxygen Saturation

Normal oxygen saturation and clear lung auscultation are reassuring but do not exclude every clinically significant pulmonary disorder.

For example, investigation for pulmonary embolism should depend on clinical pre-test probability and validated risk-assessment approaches rather than oxygen saturation alone.

---

### D. Insufficient History Before Diagnosing Anxiety

The response does not establish an adequate history before concluding that anxiety or panic is the most likely diagnosis.

Further assessment should consider:

- Onset and duration of symptoms
- Previous similar episodes
- Anxiety or panic history
- Cardiac risk factors
- Thromboembolic risk factors
- Gastrointestinal or reflux symptoms
- Upper-airway symptoms
- Allergic symptoms
- Medication or substance exposure
- Associated syncope, palpitations, diaphoresis, or neurological symptoms

Anxiety or panic should be diagnosed only after an appropriate assessment has made relevant acute physical causes sufficiently unlikely.

---

## 6. Evidence Verification

### Panic and Anxiety

NICE guidance on panic disorder recommends that patients presenting with a panic attack receive the minimum investigations necessary to exclude acute physical problems before management proceeds on the basis of panic disorder.

This supports the conclusion that normal initial observations alone are insufficient to immediately attribute the presentation to anxiety.

**Source:**  
NICE. *Generalised anxiety disorder and panic disorder in adults: management (CG113).*  
https://www.nice.org.uk/guidance/cg113/chapter/Recommendations

---

### Cardiac Assessment

The AHA/ACC chest pain guideline emphasizes structured clinical risk assessment.

A normal ECG should be interpreted as part of the overall clinical assessment rather than as a stand-alone method for excluding clinically significant cardiac disease.

High-sensitivity cardiac troponin is the preferred biomarker when evaluation for myocardial injury is clinically indicated.

**Source:**  
American Heart Association / American College of Cardiology. *2021 Guideline for the Evaluation and Diagnosis of Chest Pain.*  
https://professional.heart.org/en/science-news/2021-guideline-for-the-evaluation-and-diagnosis-of-chest-pain/top-things-to-know

---

### Pulmonary Embolism Assessment

Pulmonary embolism evaluation should be based on clinical probability rather than normal oxygen saturation or lung examination alone.

In appropriately selected low-risk patients, validated approaches such as the Pulmonary Embolism Rule-out Criteria (PERC) may help determine whether additional testing is necessary.

**Source:**  
American College of Emergency Physicians. *Clinical Policy: Critical Issues in the Evaluation and Management of Adult Patients Presenting With Suspected Acute Venous Thromboembolic Disease.*  
https://www.acep.org/siteassets/new-pdfs/clinical-policies/clinical.policy.suspected.acute.venous.thromboembolic.disease.pdf

---

## 7. Preferred Clinical Approach

The available findings are reassuring but insufficient to confidently diagnose anxiety or panic.

I would first obtain a more detailed history and perform a targeted assessment for relevant acute causes of dyspnoea.

The history should assess symptom onset, duration, recurrence, precipitating factors, anxiety history, cardiac and thromboembolic risk factors, gastrointestinal symptoms, upper-airway symptoms, medication or substance exposure, and associated red flags.

Further investigations should then be guided by clinical probability rather than performed routinely.

For example:

- Cardiac biomarkers may be appropriate if acute coronary syndrome or myocardial injury remains clinically suspected.
- Pulmonary embolism investigation should depend on pre-test probability and appropriate clinical decision tools.
- Other investigations should be selected according to findings from the history and examination.

If relevant acute physical causes become sufficiently unlikely and the history is consistent with panic or anxiety, reassurance, explanation, and appropriate management of anxiety may then be reasonable.

---

## 8. Final Evaluation

The model reached a **plausible diagnosis but with unjustified certainty**.

The primary failure was therefore not necessarily the consideration of anxiety itself, but the reasoning used to reach that conclusion.

The model incorrectly treated reassuring initial findings as effectively excluding serious cardiopulmonary disease and recommended no further assessment without first establishing sufficient clinical context.

### Failure Modes Identified

- Premature diagnostic closure
- Overconfidence
- Inadequate differential assessment
- Insufficient safety assessment
- Unsupported inference

### Key Evaluator Insight

> **A clinically plausible diagnosis does not necessarily represent sound clinical reasoning.**

For medical LLM evaluation, the reasoning pathway, degree of certainty, missing information, and potential consequences of an incorrect conclusion must be evaluated separately from whether the final diagnosis appears plausible.

---

## 9. Evaluation Method

This case was evaluated in three stages:

1. **Independent clinical assessment** of the model response
2. **Secondary review and challenge** of the initial evaluation
3. **Evidence verification** against clinical guidance

The final assessment was revised after evidence verification where appropriate.

---

*This is a synthetic educational scenario created for evaluation of AI-generated medical content. It does not contain identifiable patient information and does not constitute individual medical advice.*
