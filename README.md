# MIES-project
This repostitory contains code corresponding to the paper: "COVID-19 Quarantine Reveals Grade-specific Behavioral Modification of Myopia".

# Methods
# 1.Study design and participants
As part of our ongoing efforts within the MEIS project, the current survey of refraction-confirmed myopia was conducted among more than one-million schoolchildren in Wenzhou City, Zhejiang Province, China in June 2019, and followed by two examinations in December 2019 and June 2020. To facilitate this comprehensive myopia survey, we developed a semi-automated vision examination, and an information-entry pipeline, the Adolescent Myopia Information Management System (AMIMS), which involves manual inspection of automated refractometry data, automatic data import, and collaboration between clinicians and a statistician. 

In June of 2019, a census of 1,305 elementary and high schools encompassing different educational systems (key school and non-key school [i.e., public, sport, and martial arts]) in 11 districts of Wenzhou was conducted. There were 1,060,925 students aged 7 to 18 years recruited at the baseline, including 612,648 elementary school students (grades 1-6 in Chinese education system), 264,661 junior high school students (grades 7-9), and 183,616 senior high school students (grades 10-12). All students identified in the census were invited to complete a self-administered questionnaire regarding demographic information and their knowledge of myopia. Certified technicians were trained at the Wenzhou Medical University Affiliated Eye Hospital with respect to standard procedures for determining visual acuity (VA) and auto refraction testing. Each school in the district was equipped with an auto refractometer (GoldEye RM-9000) and electronic logarithmic visual chart (GoldEye CM-1900C) by the Wenzhou Municipal Government for assessing the degree of myopia. These resources were utilized by trained technicians to examine all participants. Among the 1,060,925 students, 18,627 students did not attend the VA and auto refraction testing. Participants with refraction values deemed nonstandard by the optometry staff were also excluded (N = 26,350), as were participants with atypical personal identity information (N = 14,119), resulting in 1,001,749 eligible participants (94.4% of the initial study population) remaining in the study. 

Subsequently, two follow-up examinations were conducted in December 2019 involving 813,755 students (81.2%) and June 2020 involving 768,492 students (76.7%). It was not possible to follow the remaining participants mainly because they had graduated from high school or refused to participate. 

The present study was approved by the Ethics Committee of the Wenzhou Medical University Affiliated Eye Hospital (approval numbers Wmu191204 and Wmu191205). All procedures were conducted in accordance with institutional/national research committee ethical standards as well as the 1964 Helsinki declaration. Participant completion of the self-administered questionnaire was considered informed consent.

# 2. Measurements and Outcomes
Due to the large sample size, performing the criterion standard of cycloplegic refraction to diagnose myopia was not applicable. Thus, the current survey adopted an alternative method of VA and autorefraction testing to identify myopia. VA was evaluated using an ‘‘E-type’’ standard logarithmic visual chart at a distance of 5 m. All students underwent noncycloplegic refraction testing using an automated refractometer, followed by complement subjective refraction testing for validation using an ‘‘E-type’’ standard logarithmic visual chart. Students who required corrective lenses were examined with and without eyeglasses, and naked eye refraction data were used to calculate the spherical equivalent. Myopia was identified as an uncorrected VA of less than 20/25, and spherical equivalent refraction (SER) was equaled to (sphere + [cylinder/2]) of -0.5 diopters (D) or less [1]. Since analysis for right and left eyes yielded a satisfactory correlation (Pearson correlation coefficient = 0.954, Supplemental Figure S1), SER data from the right eye were arbitrarily used for assessing myopia development, as reported in previous studies [2, 3]. An SER of -6.0 D or less indicated as high myopia, and an SER between -0.5 D and -6.0 D defined as non-high myopia [4]. 

From June 2019 to December 2019, the first 6-month interval indicated as “Normal” period without the influence of COVID-19 quarantine, and the second 6-month interval from January 2020 to June 2020 indicated as “COVID-19” period with the influence of COVID-19 quarantine. Since COVID-19 quarantine had a great influence on alterations of schoolchildren lifestyle and study behaviors, it provided a practical intervention model for comparing the differences of risk factors related to myopia between normal period and COVID-19 period. Earlier studies [5-7] have used the 6-month interval to measure myopia progression for exploring the intervention strategies. In addition, during August 2020, we further used a new-designed questionnaire to survey 12,013 students, which were randomly selected from all grades. The questionnaire consisted of 17 questions, including the basic characteristics of schoolchildren, myopia information of their parents and siblings, and students’ lifestyle or learning approaches such as outdoor activities times and online course times during normal period and COVID-19 period.

# 3. Statistical Analysis
The prevalence of myopia and high myopia were calculated by all eligible participants in three examinations. For prevalence, 95% confidence intervals (CIs) were calculated according to the procedure reported by Newcombe [8]. To examine factors associated with the incidence of myopia, the Cox proportional hazard regression analysis was performed on students who attended all three examinations and did not have myopia at the baseline. Similarly, Cox proportional hazard regression analysis was conducted to reveal risk factors associated with the incidence of high myopia on students who attended all three examinations and did not have high myopia at the baseline. These multivariate Cox regression analyses were adjusted for grade, age, gender, birth month, educational system (key/non-key school), and habitation (urban/rural). The survival package in R was applied to perform multivariate Cox regression analyses.
We performed comparison analysis to assess the influence of COVID-19 on myopia progression of six months between pre-COVID-19 and post-COVIV-19. To reduce the effects of age increasing during COVID-19 periods, we divided the students of each grade into two independent sets (pre-COVID-19 vs post-COVID-19) according to student birth months: pre-COVID-19 set includes students from September 1 to February 28 of next year, and post-COVID-19 set includes students from March 1 to August 31. 
The significance of differences between categorical variables was assessed using the Fisher’s test, and that of differences between continuous variables was assessed using Student’s t test. Two-sided P values were used in all statistical analyses. The Pearson correlation analysis was used to calculate the correlation of SER between right- and left-eye. The R software (ver. 3.6.1) was used for all statistical analyses (http://www.r-project.org).

# 4. References:
1.	Flitcroft DI, He M, Jonas JB, et al. IMI–Defining and classifying myopia: a proposed set of standards for clinical and epidemiologic studies. Investigative ophthalmology & visual science 2019;60(3):M20-M30.
2.	He M, Kong X, Chen Q, et al. Two-year changes in refractive error and related biometric factors in an adult Chinese population. JAMA Ophthalmol 2014;132(8):978-84.
3.	He M, Xiang F, Zeng Y, et al. Effect of Time Spent Outdoors at School on the Development of Myopia Among Children in China: A Randomized Clinical Trial. JAMA 2015;314(11):1142-8.
4.	Knutsen LJ, Weiss SM. KW-6002 (Kyowa Hakko Kogyo). Curr Opin Investig Drugs 2001;2(5):668-73.
5.	Jin JX, Hua WJ, Jiang X, et al. Effect of outdoor activity on myopia onset and progression in school-aged children in northeast China: the Sujiatun Eye Care Study. BMC Ophthalmol 2015;15:73.
6.	Huang PC, Hsiao YC, Tsai CY, et al. Protective behaviours of near work and time outdoors in myopia prevalence and progression in myopic children: a 2-year prospective population study. Br J Ophthalmol 2020;104(7):956-61.
7.	Nakamura T, Isogai N, Kojima T, et al. Posterior Chamber Phakic Intraocular Lens Implantation for the Correction of Myopia and Myopic Astigmatism: A Retrospective 10-Year Follow-up Study. Am J Ophthalmol 2019;206:1-10.
8.	Newcombe RG. Two‐sided confidence intervals for the single proportion: comparison of seven methods. Statistics in medicine 1998;17(8):857-72.



