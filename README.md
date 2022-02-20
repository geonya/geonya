# geonya

<!--START_SECTION:waka-->

name: Waka Readme

on:
schedule: # Runs at 12am IST - cron: '30 18 \* \* \*'
workflow_dispatch:
jobs:
update-readme:
name: Update Readme with Metrics
runs-on: ubuntu-latest
steps: - uses: anmol098/waka-readme-stats@master
with:
WAKATIME_API_KEY: ${{bb849743-5a88-4351-a300-838c51705d40}}
GH_TOKEN: ${{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}}
SHOW_OS: "False"
SHOW_PROJECTS: "False"
SHOW_UPDATED_DATE : "False"
SHOW_COMMIT: "True"
SHOW_LANGUAGE: "True"
SHOW_DAYS_OF_WEEK: "False"
SHOW_TIMEZONE: "False"
SHOW_EDITORS: "False"
SHOW_LANGUAGE_PER_REPO: "False"
SHOW_SHORT_INFO: "True"
SHOW_LOC_CHART: "False"

<!--END_SECTION:waka-->
