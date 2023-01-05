## 🏥Capacity and utilisation of Intensive Care Unit (ICU) beds during COVID-19 🚑

Group Name: Meow 😺   
Group Members: 
- MADINA SURAYA BINTI ZHARIN (A20EC0203)
- ADRINA ASYIQIN BINTI MD ADHA (A20EC0174)

One of the challenges that the Ministry of Health suffer during the peak season of COVID-19 was managing the Intensive Care Unit (ICU) for critical patients. They always need to make sure that the capacity and the utilisation of ICU were enough. This dataset was found from the MoH (Ministry of Health Malaysia) official Github account which presently focused on COVID-19 data, in collaboration with the COVID-19 Immunisation Task Force.

src: https://github.com/MoH-Malaysia/covid19-public/blob/main/epidemic/icu.csv  

### About Dataset 📊

This dataset contains 15656 records and 16 columns and the columns that we used are:

| Field Name | Explanation |
| ------ | ------ |
| date | yyyy-mm-dd format; data correct as of 2359hrs on that date |
| state | name of state, with similar qualification on exhaustiveness of date-state combos as PKRC data  |
| beds_icu_total| total critical care beds available (with related medical infrastructure) |
| beds_icu_covid| total critical care beds dedicated for COVID-19  |
| vent | total available ventilators |
| vent_port | total available portable ventilators|
| icu_x | total number of individuals in category x under intensive care, where x can be suspected/probable(icu_pui), COVID-19 positive(icu_covid), or non-COVID(icu_noncovid); this is a stock variable |
| vent_x | total number of individuals in category x on mechanical ventilation, where x can be suspected/probable(vent_pui), COVID-19 positive (vent_covid), or non-COVID(vent_noncovid); this is a stock variable |
