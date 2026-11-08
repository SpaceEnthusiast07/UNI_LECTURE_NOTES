
1)
$$\pi_{\text{STU-LNAME}}(\sigma_{\text{CRS-CODE} \; = \; \text{'Comp-101'}}(\text{STUDENT-1} \; \cup \; \text{STUDENT-2}))$$

2)
$$\pi_{\text{STU-LNAME}}(\sigma_{\text{MODULE-NAME} \; = \; \text{'Programming'} \; \land \; \text{EXAM-MARK} \; < \; 60}((\text{ASSESSMENT} \; \bowtie \; \text{MODULE}) \bowtie \text{STUDENT-1}))$$

3)
$$\pi_{\text{STU-NUM, STU-LNAME}}(\sigma_{\text{COURSEWORK-MARK} \; >= \; 60 \; \land \; \text{EXAM-MARK} \; >= \; 60}(\text{ASSESSMENT} \; \bowtie \; \text{STUDENT-1}))$$

4)
$$\pi_{\text{MODULE-NAME}}(\text{MODULE} \; \bowtie \; ((\text{ASSESSMENT}) \; \bowtie \; (\sigma_{\text{STU-LNAME} \; = \; \text{'Williams'}}(\text{STUDENT-1}))))$$
a) $$\sigma_{\text{STU-LNAME} \; = \; \text{'Williams'}}(\text{STUDENT-1})$$
b) $$(\text{ASSESSMENT}) \; \bowtie \; (\sigma_{\text{STU-LNAME} \; = \; \text{'Williams'}}(\text{STUDENT-1}))$$
c) $$(\text{MODULE} \; \bowtie \; ((\text{ASSESSMENT}) \; \bowtie \; (\sigma_{\text{STU-LNAME} \; = \; \text{'Williams'}}(\text{STUDENT-1}))))$$


