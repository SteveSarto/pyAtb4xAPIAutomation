Python API Automation Framework

Tech Stack
Python 3.12
Requests- HTTP Requests
Pytest - Testing Framework
Reporting- allure Report,Pytest HTML
Test Data-CSVExcel,JSON,Faker
Advance API Testcase - jsonschema
Parallel Execution - x distribute(Xdist)

How to run your Testcase Parallel pip install pytest-xdist 

How to run the Basic Test with Allure report

 pytest tests/tests/crud/test_create_booking.py  --alluredir=allure_result -s