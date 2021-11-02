```Python
from "AbidzarMGK" import resume
from datetime import datetime

class bio(resume):
  def __init__(self):
    self.name = "Abidzar M. G. Kurniawan"
    self.title = "Software Engineer"
    self.experience = [{
      "occupation": "Backend Engineer Intern",
      "location": "Information Technology Center Directorate, Telkom University",
      "start_date": datetime(2021, 2, 1),
      "end_date": datetime(2021, 7, 31)
    },{
      "occupation": "Data Engineer Intern",
      "location": "PT Telekomunikasi Selular",
      "start_date": datetime(2019, 6, 10),
      "end_date": datetime(2019, 8, 10)
    }]
    
class skill(resume):
  def __init__(self):
    self.language = ["Python","Javascript"]
    self.database = ["MySQL","PostgreSQL","MongoDB"]
    self.technology = ["NodeJS","ExpressJS","Postman","VSCode","Github"]
```
