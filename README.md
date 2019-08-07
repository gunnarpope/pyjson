# pyjson
Simplifying loading, handling, and saving JSON formatted objects with python

@gunnarpope on telegram

8/8/19

# Usage

	>>> import pyjson as json
	>>> dat = json.jsonLoad('data.json')
	>>> dat
	{'username': 'bob', 'password': 'badpassword'}
	>>> json.jsonSave(dat,'data2.json')
	Success: Data saved to JSON file:  data2.json
	>>> dat2 = json.jsonLoad('data2.json')
	>>> dat2
	{'username': 'bob', 'password': 'badpassword'}
