# Sleep-and-Mental-Health-in-Atopic-Dermatitis
Codelists, exposure/outcome definitions and algorithms for "The mental health burden in children with atopic dermatitis and sleep disturbance: A retrospective matched cohort study in England" study by Momentum Data.

## Quality control
All the codelists utilised for data extraction underwent the rigorous quality control process utilised by Momentum Data for multiple real world evidence studies. This process consisted of manual code list generation by a coding expert with a clinical background. The list was then independently reviewed by a second coding expert. The lists then went through an automated quality control process to identify any potential formatting errors or coding inconsistencies. During the data extraction process, high frequency codes were independently reviewed by a third reviewer to ensure that the most commonly used codes correctly match the clinical entity they are being used to identify. A fourth quality control step looks for overlap between code or case definitions where multiple definitions are possible e.g., biochemical disease markers and clinical diagnosis codes for a condition. Finally once variables were generated, the frequency and pattern of variable prevalence was compared with known data from previous analysis in other independent datasets and published literature. Any inconsistencies were reviewed and investigated as appropriate.

## Algorithms for identification
All of the conditions and medications mentioned below will use diagnostic codes recorded in primary care **only** (Read V2, Read CTV3 and SNOMED).

### Atopic Dermatitis (AD)
AD will be identified and defined using a validated AD case definition.[^1] AD case identification will use a combination of AD specific diagnosis codes and two or more AD treatment prescribed on different dates.

- People identified with a specific diagnosis code for [AD](https://github.com/MomentumData/Momentum-Data-Codelists/tree/0402c36e3628604fa4df5b0254d76b0449f1bda0/Conditions/AD%20(Atopic%20Dermatitis))

### AD treatments
- [Emollients]()

- [Topical Steroids]():
  - [Very potent topical steroids]()
  - [Potent topical steroids]()
  - [Moderate topical steroids]()
  - [Mild topical steroids]()
  
- [Topical calcineurin inhibitors]()
  
- [Topical anti-infective treatments]()
  
- Systemic immunosuppressant treatments:
  - [Methotrexate](https://github.com/MomentumData/Momentum-Data-Codelists/tree/d5b18be4932e2467067cf1bb028ef7b92ecb2c58/Treatments/Methotrexate)
  - [Azathioprine](https://github.com/MomentumData/Momentum-Data-Codelists/tree/d5b18be4932e2467067cf1bb028ef7b92ecb2c58/Treatments/Azathioprine)
  - [Mycophenolate]()
  - [Ciclosporin](https://github.com/MomentumData/Momentum-Data-Codelists/tree/d5b18be4932e2467067cf1bb028ef7b92ecb2c58/Treatments/Ciclosporin)
  - Biologics:
    - [Dupilumab]()
      
- [Phototherapy]()
  
- [Dermatology Referrals]()

### AD severity
AD severity will be defined using AD treatments utilizing a validated definition which has been previously implemented using primary care records.[^2] 
- AD is considered mild, by default.
- AD is considered moderate, following the prescription of a second potent topical steroid treatment within one year or a first topical calcineurin inhibitor.
- AD is considered severe, at the first prescription of a systemic immunosuppressant treatment (ciclosporin, azathioprine, mycophenolate, methotrexate and biologics), phototherapy or a dermatology referral.
  
For an individual patient with active AD, severity can change during the study follow-up: once fulfilling criteria for moderate AD, cases remain as moderate unless they develop severe AD. When fulfilling criteria for severe AD, cases remained as severe for the remainder of their follow-up.

### Sleep disturbance
People identified with a diagnosis code for for [sleep disturbance](https://github.com/MomentumData/Momentum-Data-Codelists/tree/0402c36e3628604fa4df5b0254d76b0449f1bda0/Conditions/Sleep%20disturbance)

### Asthma
- [Asthma](https://github.com/MomentumData/Momentum-Data-Codelists/tree/d5b18be4932e2467067cf1bb028ef7b92ecb2c58/Conditions/Asthma)

### Atopic comorbidity
Any of:
- [Asthma](https://github.com/MomentumData/Momentum-Data-Codelists/tree/d5b18be4932e2467067cf1bb028ef7b92ecb2c58/Conditions/Asthma)
- [Allergic rhinitis]()
- [Urticaria]()

### Allergic comorbidity
Any of:
- [Asthma](https://github.com/MomentumData/Momentum-Data-Codelists/tree/d5b18be4932e2467067cf1bb028ef7b92ecb2c58/Conditions/Asthma)
- [Allergic rhinitis]()
- [Urticaria]()
- [Food Allergy]()

### Autism
- [Autism]()

### Attention Deficit Hyperactivity Disorder (ADHD)
- [ADHD]()

### Mental health outcomes

#### Depression
Any of:
- People identified with a diagnosis code for [recurrent depressive disorder](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/RDD%20(Recurrent%20Depressive%20Disorder)).
- People identified with a diagnosis code for [depressive episode](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/Depressive%20Episodes)

#### Anxiety
People identified with a diagnosis code for [anxiety episode](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/Anxiety%20Episode)

#### [Attention Deficit Hyperactivity Disorder (ADHD)]()

#### [Behavioural and conduct disorders]()

# References
[^1]: de Lusignan S, Alexander H, Broderick C, et al. Epidemiology and management of atopic dermatitis in England: an observational cohort study protocol. BMJ Open 2020;10(9):e037518. doi: 10.1136/bmjopen-2020-037518
[^2]: Tippu Z, Correa A, Liyanage H, et al. Ethnicity Recording in Primary Care Computerised Medical Record Systems: An Ontological Approach. J Innov Health Inform 2017;23(4):920. doi: 10.14236/jhi.v23i4.920 [published Online First: 2017/03/28]
