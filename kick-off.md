# Project Athena Kick-Off

**SARS-CoV-2 is still spreading fast, leading to a global crisis. A crisis is scary when you are limited to observe it. However, we can do something. We can help to change the course of this crisis by taking action.** 

A short reminder - project Athena aims to focus efforts to provide actionable insights for SARS-CoV-2. A committee will be setup to steer our efforts. The committee will be overlooking several continuous workstreams:

1. **Information gathering** - collect information on latest research on SARS-CoV-2, especially medical and epidemiological work 
2. **Need identification** - identify research and product development needs. We reach out to research communities or other groups and identify stakeholders who have a need that we can deliver upon
3. **Postulate hypothesis** - collect and decide upon hypothesis to evaluate
4. **Data baseline** - Provide access to high quality data so hypothesis can be tested - we collect data for use cases only! 
5. **Review and publish** - Review our research results and publish them for external feedback
6. **Supporting processes and tools** - Communication and documentation infrastructure needs to be setup. How do we enable maximum autonomy for individuals and teams whilst keeping an overview of our initiatives.
7. **Athena committee** - who will participate and how will the committee work, what is the cadence of meetings and which meetings will we need?

For each of these work streams, we will need a lead person who will drive and coordinate the work and will participate in the Athena committee. The Athena committee will maintain a website, for now https://github.com/alexander-stage/athena.

## Potential Bootstrapping Hypothesis

1. **"What we observe"**
    * **Observations and assumptions** 
    
        Based on publicly available data from affected countries on infected, death and recovered cases, the spread seems to follow an exponential growth path. 
        However differences between countries exist in growth factors, fatality, speed of recovery, ratios between various measurements, time lags, testing and many more. 
        
    * **Hypothesis**
    
        1. The virus is spreading at an exponential rate of 1.2 day to day.
        2. Mortality is non-homogenous across countries or regions, varies significantly between countries
  

2. **"What we suspect"**
    * **Observations and assumptions**
        
        Not everyone with a SARS-CoV-2 infection will feel ill. Some people may even contract the virus and not develop symptoms. When there are symptoms, they’re usually mild and tend to come on slowly. There are estimates taht 50% of cases of the coronavirus disease (COVID-19) take an asymptomatic course. Therefore a lot of cases have gone unnoticed as wide-spread testing is not available.
        
    * **Hypothesis**
    
        1. The real number of infected people is 300% higher than officially reported numbers.
        

3. **"What we need to know"**
    * **Observations and assumptions**
    
        COVID-19 seems to cause more severe symptoms in older adults and people with underlying health conditions, such as chronic heart or lung conditions. In some countries the age distribution of infected people does represent the general age distribution with the region or country.
        In Italy, a country with a rather old population, a analysis found that of the 105 patients at that time who died from the virus, the average age was 81 years. This puts a 20-year gap between the average age of people who tested positive for the virus and the deceased.

    * **Hypothesis**
    
        1. Mortality adjusted by age and country is below 1%
        
4. **"What we speculate"**
    * **Observations and assumptions**
        
        Testing for SARS-CoV-2 has been limited and apparently only carried out for people who have shown severe symptoms. Switzerland for example only tests elderly and obviously sick people. The tests used so far have no reported statistics on their false positive or false negative percentages. The amount of deaths accounted to SARS-CoV-2 could be misleading if for example a lot of false positives are generated.
        
    * **Hypothesis**
    
        1. The differences in testing, widespread versus focused, lead to significant differences in case numbers (infected, recovered, deaths)
        2. 50% of all deaths can not be directly linked to a SARS-CoV-2 infection.
            
## Product Ideas

1. **Mobile phone based monitoring system (for hospitals)** - COVID-19 may affect the lungs causing pneumonia. In those most severely affected, COVID-19 may rapidly progress to acute respiratory distress syndrome causing respiratory failure. When the disease progresses to this critical state, our hypethesis is that breathing sounds change giving an potentially early indicator for doctors to change the treatment.

    Minimum viable product: 
    
    1. Use patients mobile phone to record breathing sounds. 
    2. Register the phones in an anonymous way a allow hospitals to map phones to beds or patients.
    3. Display breathing sounds to doctors.
    
    Next steps:
    
    1. Analyse breathing sounds and implement change point detection which can trigger alerts.
