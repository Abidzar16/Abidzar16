```Python
from "AbidzarMGK" import resume
from datetime import datetime

class bio(resume):
  def __init__(self):
    self.name = "Abidzar M. G. Kurniawan"
    self.title = "Software Engineer"
    self.experience = [
    {
      "occupation": "FUll Stack Developer at PT Infomedia Nusantara",
      "location": "Jakarta",
      "start_date": datetime(2024, 08, 12)
    },{
      "occupation": "Backend Engineer Ihsan Solusi Informatika",
      "location": "Bandung",
      "start_date": datetime(2023, 10, 20),
      "end_date": datetime(2024, 01, 11)
    },{
      "occupation": "Backend Mentor at Studi Independen Startup Campus",
      "location": "Remote",
      "start_date": datetime(2022, 6, 1),
      "end_date": datetime(2022, 12, 31)
    },{
      "occupation": "Backend Mentor at Studi Independen Ruangguru",
      "location": "Remote",
      "start_date": datetime(2022, 2, 1),
      "end_date": datetime(2022, 5, 31)
    },{
      "occupation": "Backend Engineer Intern at Telkom University",
      "location": "Remote",
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
    self.language = ["Python","NodeJS", "Go"]
    self.database = ["MySQL","PostgreSQL","MongoDB","OracleDB"]
    self.technology = ["NodeJS","ExpressJS","Postman","VSCode","Github"]
```
