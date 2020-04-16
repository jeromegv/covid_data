# covid_data

Daily automatic scripts to retrieve COVID data that is likely to disappear from the public domain at some point
My daily scripts are also submitting all the files to the [Internet Archive](https://archive.org) under their original URL schema

## ontario/epidemiological_summary
- Ontario Epidemiological Summary for COVID-19
- PDF archives from Public Health Ontario at https://www.ontario.ca/page/2019-novel-coronavirus
- Automatic daily updates

## ontario/status_of_cases_in_ontario
- Status of cases in Ontario
- HTML output of what is visible every day on https://www.ontario.ca/page/2019-novel-coronavirus
- Getting the HTML output using: https://api.ontario.ca/api/drupal/page%2F2019-novel-coronavirus?fields=body
- Automatic daily updates

## quebec/situation_html_output
- Situation du coronavirus (COVID-19) au Québec / Situation of the coronavirus (COVID-19) in Québec
- Daily HTML output of https://www.quebec.ca/sante/problemes-de-sante/a-z/coronavirus-2019/situation-coronavirus-quebec/
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
