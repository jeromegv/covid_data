# covid_data

Daily automatic scripts to retrieve COVID data that is likely to disappear from the public domain at some point
My daily scripts are also submitting all the files to the [Internet Archive](https://archive.org) under their original URL schema

## ontario/epidemiological_summary
- Ontario Epidemiological Summary for COVID-19
- PDF archives from Public Health Ontario at https://www.ontario.ca/page/2019-novel-coronavirus
- Automatic daily updates

## ontario/status_of_cases_in_ontario
- Status of cases in Ontario
- HTML output of what is visible every day on https://www.ontario.ca/page/how-ontario-is-responding-covid-19
- Getting the HTML output using: https://api.ontario.ca/api/drupal/page%2Fhow-ontario-is-responding-covid-19?fields=body
- Automatic daily updates

## quebec/situation_html_output
- Situation du coronavirus (COVID-19) au Québec / Situation of the coronavirus (COVID-19) in Québec
- Daily HTML output of https://www.quebec.ca/sante/problemes-de-sante/a-z/coronavirus-2019/situation-coronavirus-quebec/
- Automatic daily updates

## canada/full_epidemiological_report
- Daily Epidemiology Update - Full Epidemiological report from the Government of Canada
- Daily download of the full epidemiological report PDF https://www.canada.ca/content/dam/phac-aspc/documents/services/diseases/2019-novel-coronavirus-infection/surv-covid19-epi-update-eng.pdf
- Automatic daily updates

## canada/full_epidemiological_report/csv
- CSV files being used to generate the graphics and charts on the page "Epidemiological summary of COVID-19 cases in Canada" https://health-infobase.canada.ca/covid-19/epidemiological-summary-covid-19-cases.html
- Automatic daily updates

## canada/current_situation_csv
- Daily download of CSV https://health-infobase.canada.ca/src/data/covidLive/covid19.csv , which is the CSV linked from the main graphic on https://www.canada.ca/en/public-health/services/diseases/2019-novel-coronavirus-infection.html
- Automatic daily updates

## canada/outbreak_update
- Coronavirus disease (COVID-19): Outbreak update from the Government of Canada
- HTML output of what is visible every day on https://www.canada.ca/en/public-health/services/diseases/2019-novel-coronavirus-infection.html
- Automatic daily updates

## google_community_mobility_reports
- Google COVID-19 Community Mobility Reports. 
- PDF archives from: https://www.google.com/covid19/mobility/
- Google releases new data at an irregular interval (every few days)

## apple_mobility_trends_reports
- Apple Maps Mobility Trends Reports
- Daily CSV archives from: https://www.apple.com/covid19/mobility
- Automatic daily updates

## who_situation_reports
- World Health Organization Situation Reports
- Daily PDF archives from WHO: https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports
- Automatic daily updates
