# OPEN-INVESTIGATION

## U.N. REFUGEE AND ASYLEE PROGRAM

## 1951 THRU 2024*

### United Nations data reveals >50 Million 'refugees and asylees' resettled into the USA

The U.N. UNHCR has a mandate granting oversight of refugees and asylees throughout the world. This oversight excludes aliens who have arrived via border crossings, so called 'Got-a-Ways', actual migrants, or even VISA overstays.  Figures provided by the U.N. only address (with emphasis) refugees and asylees.  Focusing on the United States for a moment, with regards to the U.N. records for the U.S. as country of asylum, U.N. oversight figures for refugees are orders of magnitude annually higher than U.S. congressional ceilings allow, noting U.S. official government reports only identify a fraction of what U.N. records reveal.  This difference for the U.S. calls into question the level of U.S. government reporting accuracy that Congress relies upon, as annual ceiling limits of refugees are annually broken according to U.N. provided records.  From this U.N. data, It appears the United States Congress may systemically rely upon inaccurate internal government reports.  This U.N. extracted dataset contains all currently available data for refugees and asylees ordered by country of asylum.  While the primary focus of this README centers on the U.S., the same granular national dataset is made available here, extracted from the U.N. database - current as of October 15th, 2024.  Disparaging differences in U.S. internal reports vs U.N. reports on the U.S., as well as reporting differences with other nations and U.N. reports on the same require an **Open-Investigation** to get nearer to the actual truth.

### United Nations High Commissioner for Refugees (UNHCR)

The UNHCR is a multilateral intergovernmental institution given a core mandate in 1949 established by the UN General Assembly.  Additional powers were granted by the Economic and Social Council [ESOSOC].  Through public international law and international treaty law, governments are obligated to cooperate involving the protection of refugees, and it intercedes directly on behalf of refugees and stateless persons.  UNHCR is also empowered to invite/solicit cooperation with varioius specialized agencies towards performance of its mandate.  UNHCR collaborates with Governments, develops partnerships with other international agencies and non-governmental organizations (NGO).  The UNHCR has established an interlocking network of collaboration that advances assistance and protection of refugees and asylees.  [The mandate of the High Commissioner for Refugees and his Office | UNHCR US](https://www.unhcr.org/us/media/mandate-high-commissioner-refugees-and-his-office)

#### Definition of Refugees and Asylees do NOT include Migrants

The UNHCR states the term 'migrant' is not defined under international law, and the UN's involvement does not extend to 'migrants'. Two categories of people are covered by the UN: Refugees and Asylum-Seekers. The 'Refugee' is defined as anyone outside their country of origin for reasons of feared persecution, conflict, generalized violence or other circumstances that have seriously disturbed public order. The 'Asylum-seeker' is defined as anyone whose 'Refugee' status has not yet been determined by authorities, but whose claim to international protection entitles the individual to a certain protective status on the basis the individual 'could' be a 'Refugee', or where persons forming a large-scale influx of mixed groups in a situation where individual 'Refugee' status determination....is impractical. They may also be called 'prima facie' refugees.  However, as 'migrant' is not defined, such numbers are not recorded.  By definition, border crossers, migrants, so-called got-a-ways and VISA overstays are excluded by definition. [Migrant definition | UNHCR](https://emergency.unhcr.org/protection/legal-framework/migrant-definition)

#### On the Quality of UNHCR Data

The international data extracted from the U.N. is data made available through the UNHCR mandate and reveals figures that extend by definition to Government collaboration in their accuracy.  There is no underlying reason currently identified that would either question UN UNHCR figures, or question the granular level of data such as Country of Origin information, annual totals, or figures identifying the small handful returned to their Country of Origin on any given year.  These datasets should be considered definitive.

#### UNHCR Reveals Apparent Underreporting by U.S. Government

The U.N. data for the U.S. as country of asylum, when compared with official U.S. government reports prepared by OHSS, DHS and DOJ reveals apparent systemic underreporting of head counts within U.S. Government published reports.

Examination performed on the following OHSS, DHS and DOJ reports (FY1997INS-2022):

[Refugees and Asylees Annual Flow Report | Homeland Security](https://www.dhs.gov/ohss/topics/immigration/refugees-asylees-afr)

It must be noted that refugee is a group congressionally restricted by annual ceiling. UNHCR figures for the U.S. systematically exceed the ceilings established by U.S. law.  This situation brings into question not only apparent underreporting by OHSS, DHS and DOJ, but the implications of annually breaking through the limit of congressional ceiling.  It would appear, Congress is unaware of these disparaging differences based on available reports.  This difference also brings into question a larger issue surrounding the circumstances of those that prepared such reports, as well as if any laws may have been broken in the providing and publishing of potentially inaccurate government information.  Those are questions for lawmakers, investigators and others to answer.  Regardless, IF U.S. reports on refugee admissions, and total individuals granted asylum affirmatively or defensively are difinitively proven in fact to be willfully and wontonly underreported in U.S. available government reports, much larger questions, concern and need for action begins to emerge - which may require an **Open-Investigation**.

### Data Comparison UNHCR | OHSS, DHS and DOJ Reports

UN UNHCR USA DATA vs US GOV FY1997INS-2022 REPORTS

![alt text](https://github.com/arch-beard/OPEN-INVESTIGATION/blob/main/DATA_UNHCR_vs_OHSS_DHS_DOJ.jpg?raw=true)

### PURPOSE OF THIS REPOSITORY

This repository is international supporting evidence for all available nations that have received refugees and asylees, managed or provided by the U.N. , that is data pulled direct from official U.N. database - through public API query as received in JSON format.  The raw data received by the U.N. is also converted for wider usability into CSV and XLSX for use with common software such as Microsoft Excel and Open Office.

### Special Notes

While initial focus concerns refugees and asylees numbers for the U.S., the data is available on every nation and is published here.  Each element from the dataset is useful for more in-depth data analysis.  Useful data fields are: Country of Origin (coo_id, coo_name, coo, coo_iso), Country of Asylum (coa_id, coa_name, coa, coa_iso), quantity of refugees by country of origin with specified country of asylum on any given year (refugees), quantity of asylees by country of origin with specified country of asylum on any given year (asylum_seekers), quantity that were returned to country of origin on any given year (returned_refugees), quantity of refugees and asylees claiming to be stateless on any given year (stateless category and field under Country of Origin).  Such information allows for larger analysis with Country of Origin data by year, which should expose potential change related issues in a receiving nation.  The data may also be more interesting when joined with other available datasets to calculate correlations or potentially identify direct relationships from such movements.

In some instances, the U.N. did not present data for some countries. Positive and NULL responses are included within the dataset, and reflects the raw nature of the query.

The UNHCR uses the following country naming conventions through their API query which is dutifully maintained within the respective country of asylum filenames found in this repository.  The Country ISO standard as well as the country name of asylum is clearly presented within the actual data.

###### AFG,ALB,ALG,AND,ANG,ANT,ARE,ARG,ARM,AUL,AUS,AZE,BAH,BAR,BDI,BEL, BEN,BER,BGD,BHS,BHU,BKF,BLR,BOL,BOT,BRA,BRU,BSN,BUL,BZE,CAM,CAN, CAR,CAY,CHD,CHI,CHL,CMR,COB,COD,COI,COL,COS,CUB,CUW,CVI,CYP,CZE, DEN,DJB,DMA,DOM,ECU,EGU,ERT,EST,ETH,FGU,FIJ,FIN,FNC,FRA,FSM,GAB, GAM,GAZ,GBR,GEO,GFR,GHA,GIB,GLP,GNB,GRE,GRN,GUA,GUI,GUY,HAI,HKG, HON,HRV,HUN,ICE,ICO,IND,INS,IRE,IRN,IRQ,ISR,ITA,JAM,JOR,JPN,KAZ, KEN,KGZ,KIR,KOR,KRN,KUW,LAO,LBR,LBY,LCA,LEB,LES,LKA,LTU,LVA,MAC, MAD,MAU,MCD,MCO,MDA,MDV,MEX,MHL,MLI,MLS,MLW,MNE,MNG,MOR,MOZ,MTA, MTS,MYA,NAM,NEP,NET,NGR,NIC,NIG,NIU,NRU,NZL,OMN,PAK,PAN,PAR,PER, PHI,POL,POR,QAT,ROM,RSA,RUS,RWA,SAL,SAU,SEN,SEY,SIN,SLE,SMA,SOM, SPA,SRB,SRV,SSD,STA,STK,SUD,SUR,SVK,SVN,SWA,SWE,SWI,SYR,TAN,TCI, THA,TJK,TKM,TMP,TOG,TON,TRT,TUN,TUR,UAE,UGA,UKN,UKR,URU,USA,UZB, VAN,VCT,VEN,WES,YEM,ZAM,ZIM

Each API query explicitly requested all available data from the UNHCR database ranging from 1951 thru 2024.

[UNHCR Public Query](https://www.unhcr.org/refugee-statistics/download/)

[UNHCR - Global Public API](https://api.unhcr.org/population)

This information is brought to you by: [Arch Beard](https://gab.com/ArchBeard)

UNITED NATIONS IS CREDITED AS THE PRIMARY DATA SOURCE. ALL ATTEMPTS FOR ACCURACY IS MAINTAINED. DUE DILIGENCE IS ATTEMPTED AT ALL TIMES AND PERFORMED IN GOOD FAITH. RIGHTS ARE RETAINED BY THE UNITED NATIONS. FAIR USE IS CLAIMED WITH THIS PRESENTATION OF U.N. DATA AS IT IS IN THE PUBLIC INTEREST.
