## Description: Download metadata for SCORES from the Google Apps Script web app.
##

SCRIPT_URL = https://script.google.com/macros/s/AKfycby1DZKPzwHraHCRLXgjHrWYoIosgALmQHG_TtVoqxl5A_Wj3JzeYX3FY0_eAPbJ1Iebcw/exec

all: download

download: works

works:
	curl -L "$(SCRIPT_URL)?sheet=works" > works.json

clean:
	rm -f works.json