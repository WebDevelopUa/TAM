# TAM
## Анализ рисков безопасности приложений используя 


**Microsoft Threat Analysis & Modeling v2.1.2**

https://www.microsoft.com/en-us/download/confirmation.aspx?id=14719

https://download.microsoft.com/download/3/4/3/343e79df-52bf-46a3-92f7-edeaa0f660a0/TAMv2.1.2.msi




**Microsoft .NET Framework 3.5**

https://www.microsoft.com/en-us/download/details.aspx?id=21

https://download.microsoft.com/download/7/0/3/703455ee-a747-4cc8-bd3e-98a615c3aedb/dotNetFx35setup.exe



#### Sample #1

Model with two roles: ***admin*** and ***patient***



| Data                            | Role         | Permissions  |
| ------------- |                 :-------------:|  -----:|
| patient personal information    | admin       | Create, Read, Update, Delete |
| patient personal information    | patient     |  Read, Update |
| message                         | admin       | Create, Read, Delete  |
| message                         | patient     | Create, Read, Delete |

 




| Component      | Relevancies  |
| -------------  |:------------- | 
| Tomcat         | exposes a Web browser interface, utilizes HTTP, utilizes a network protocol   | 
| MySQL          | utilizes a network protocol     | 
| Servlets       | admin       | exposes a web browser interface, utilizes HTTP, performs arithmetic operations, constructs SQL queries
 

 
[Project file](Test-Threat-Model-01.atmx "Sample #1 Project file") |  [Report file](Threat_Model_1-Comprehensive_Report.mht "Sample #1 Report file")

 

***



P.S.

 
***Microsoft Security Assessment Tool (MSAT)*** — это средство оценки рисков, предоставляющее информацию о системе безопасности ИТ-инфраструктуры и рекомендации по ее улучшению, основанные на передовом опыте.

**Microsoft Security Assessment Tool 4.0**

https://www.microsoft.com/en-us/download/details.aspx?id=12273

https://download.microsoft.com/download/D/A/0/DA0E6A3D-648A-4136-ACB6-556214F13D8F/MSAT%20Russian.zip

Данное средство использует целостный подход к оценке системы безопасности, анализируя влияние человеческого фактора, процессов и технологий. Полученные результаты предоставляются пользователям вместе с подробным руководством, рекомендациями по снижению угроз и ссылками на отраслевые руководства, содержащие дополнительные сведения. Эти ресурсы могут помочь организациям получить информацию о средствах и методах, способных повысить безопасность ИТ-среды организации.

***Microsoft Security Assessment Tool*** позволяет оценить следующие характеристики. 
•	Профиль риска для бизнеса. 
•	Многоуровневая защита (ОБНОВЛЕНО). 
