artillery run prod_lamb.yml



locust -f locust_test.py --host=http://localhost:8050/
locust -f locust_test.py --host=http://wkpdfgen-prod.eba-78arf59s.ap-south-1.elasticbeanstalk.com/

