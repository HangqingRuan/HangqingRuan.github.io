---
layout:     post   				    # 使用的布局（不需要改）
title:      ONET DATA MERGE CODE 				# 标题 
subtitle:   How to merge the ONET occupation data with census occupation variable #副标题
date:       2019-12-18 				# 时间
author:     Ruan						# 作者
header-img: 	#这篇文章标题背景图片
catalog: true 						# 是否归档
tags:								#标签
    - Data
---

| 11-1011.00 | Chief Executives                                                                                            | 1     |
|------------|-------------------------------------------------------------------------------------------------------------|-------|
| 11-1011.03 | Chief Sustainability Officers                                                                               | 2     |
| 11-1021.00 | General and Operations Managers                                                                             | 3     |
| 11-1031.00 | Legislators                                                                                                 | 4     |
| 11-2011.00 | Advertising and Promotions Managers                                                                         | 5     |
| 11-2021.00 | Marketing Managers                                                                                          | 6     |
| 11-2022.00 | Sales Managers                                                                                              | 7     |
| 11-2032.00 | Public Relations Managers                                                                                   | 8     |
| 11-2033.00 | Fundraising Managers                                                                                        | 9     |
| 11-3012.00 | Administrative Services Managers                                                                            | 10    |
| 11-3013.00 | Facilities Managers                                                                                         | 11    |
| 11-3013.01 | Security Managers                                                                                           | 12    |
| 11-3021.00 | Computer and Information Systems   Managers                                                                 | 13    |
| 11-3031.00 | Financial Managers                                                                                          | 14    |
| 11-3031.01 | Treasurers and Controllers                                                                                  | 15    |
| 11-3031.03 | Investment Fund Managers                                                                                    | 16    |
| 11-3051.00 | Industrial Production Managers                                                                              | 17    |
| 11-3051.01 | Quality Control Systems Managers                                                                            | 18    |
| 11-3051.02 | Geothermal Production Managers                                                                              | 19    |
| 11-3051.03 | Biofuels Production Managers                                                                                | 20    |
| 11-3051.04 | Biomass Power Plant Managers                                                                                | 21    |
| 11-3051.06 | Hydroelectric Production Managers                                                                           | 22    |
| 11-3061.00 | Purchasing Managers                                                                                         | 23    |
| 11-3071.00 | Transportation, Storage, and Distribution Managers                                                          | 24    |
| 11-3071.04 | Supply Chain Managers                                                                                       | 25    |
| 11-3111.00 | Compensation and Benefits Managers                                                                          | 26    |
| 11-3121.00 | Human Resources Managers                                                                                    | 27    |
| 11-3131.00 | Training and Development Managers                                                                           | 28    |
| 11-9013.00 | Farmers, Ranchers, and Other   Agricultural Managers                                                        | 29    |
| 11-9021.00 | Construction Managers                                                                                       | 30    |
| 11-9031.00 | Education and Childcare Administrators, Preschool and Daycare                                               | 31    |
| 11-9032.00 | Education Administrators, Kindergarten through Secondary                                                    | 32    |
| 11-9033.00 | Education Administrators, Postsecondary                                                                     | 33    |
| 11-9039.00 | Education Administrators, All Other                                                                         | 34    |
| 11-9041.00 | Architectural and Engineering Managers                                                                      | 35    |
| 11-9041.01 | Biofuels/Biodiesel Technology and Product Development Managers                                              | 36    |
| 11-9051.00 | Food Service Managers                                                                                       | 37    |
| 11-9071.00 | Gambling Managers                                                                                           | 38    |
| 11-9072.00 | Entertainment and Recreation Managers, Except Gambling                                                      | 39    |
| 11-9081.00 | Lodging Managers                                                                                            | 40    |
| 11-9111.00 | Medical and Health Services Managers                                                                        | 41    |
| 11-9121.00 | Natural Sciences Managers                                                                                   | 42    |
| 11-9121.01 | Clinical Research Coordinators                                                                              | 43    |
| 11-9121.02 | Water Resource Specialists                                                                                  | 44    |
| 11-9131.00 | Postmasters and Mail Superintendents                                                                        | 45    |
| 11-9141.00 | Property, Real Estate, and Community   Association Managers                                                 | 46    |
| 11-9151.00 | Social and Community Service Managers                                                                       | 47    |
| 11-9161.00 | Emergency Management Directors                                                                              | 48    |
| 11-9171.00 | Funeral Home Managers                                                                                       | 49    |
| 11-9179.00 | Personal Service Managers, All Other                                                                        | 50    |
| 11-9179.01 | Fitness and Wellness Coordinators                                                                           | 51    |
| 11-9179.02 | Spa Managers                                                                                                | 52    |
| 11-9199.00 | Managers, All Other                                                                                         | 53    |
| 11-9199.01 | Regulatory Affairs Managers                                                                                 | 54    |
| 11-9199.02 | Compliance Managers                                                                                         | 55    |
| 11-9199.08 | Loss Prevention Managers                                                                                    | 56    |
| 11-9199.09 | Wind Energy Operations Managers                                                                             | 57    |
| 11-9199.10 | Wind Energy Development Managers                                                                            | 58    |
| 11-9199.11 | Brownfield Redevelopment Specialists and Site Managers                                                      | 59    |
| 13-1011.00 | Agents and Business Managers of   Artists, Performers, and Athletes                                         | 60    |
| 13-1021.00 | Buyers and Purchasing Agents, Farm Products                                                                 | 61    |
| 13-1022.00 | Wholesale and Retail Buyers, Except Farm Products                                                           | 62    |
| 13-1023.00 | Purchasing Agents, Except Wholesale, Retail, and Farm Products                                              | 63    |
| 13-1031.00 | Claims Adjusters, Examiners, and Investigators                                                              | 64    |
| 13-1032.00 | Insurance Appraisers, Auto Damage                                                                           | 65    |
| 13-1041.00 | Compliance Officers                                                                                         | 66    |
| 13-1041.01 | Environmental Compliance Inspectors                                                                         | 67    |
| 13-1041.03 | Equal Opportunity Representatives and Officers                                                              | 68    |
| 13-1041.04 | Government Property Inspectors and Investigators                                                            | 69    |
| 13-1041.06 | Coroners                                                                                                    | 70    |
| 13-1041.07 | Regulatory Affairs Specialists                                                                              | 71    |
| 13-1041.08 | Customs Brokers                                                                                             | 72    |
| 13-1051.00 | Cost Estimators                                                                                             | 73    |
| 13-1071.00 | Human Resources Specialists                                                                                 | 74    |
| 13-1074.00 | Farm Labor Contractors                                                                                      | 75    |
| 13-1075.00 | Labor Relations Specialists                                                                                 | 76    |
| 13-1081.00 | Logisticians                                                                                                | 77    |
| 13-1081.01 | Logistics Engineers                                                                                         | 78    |
| 13-1081.02 | Logistics Analysts                                                                                          | 79    |
| 13-1082.00 | Project Management Specialists                                                                              | 80    |
| 13-1111.00 | Management Analysts                                                                                         | 81    |
| 13-1121.00 | Meeting, Convention, and Event   Planners                                                                   | 82    |
| 13-1131.00 | Fundraisers                                                                                                 | 83    |
| 13-1141.00 | Compensation, Benefits, and Job   Analysis Specialists                                                      | 84    |
| 13-1151.00 | Training and Development Specialists                                                                        | 85    |
| 13-1161.00 | Market Research Analysts and Marketing Specialists                                                          | 86    |
| 13-1161.01 | Search Marketing Strategists                                                                                | 87    |
| 13-1199.00 | Business Operations Specialists, All Other                                                                  | 88    |
| 13-1199.04 | Business Continuity Planners                                                                                | 89    |
| 13-1199.05 | Sustainability Specialists                                                                                  | 90    |
| 13-1199.06 | Online Merchants                                                                                            | 91    |
| 13-1199.07 | Security Management Specialists                                                                             | 92    |
| 13-2011.00 | Accountants and Auditors                                                                                    | 93    |
| 13-2022.00 | Appraisers of Personal and Business Property                                                                | 94    |
| 13-2023.00 | Appraisers and Assessors of Real Estate                                                                     | 95    |
| 13-2031.00 | Budget Analysts                                                                                             | 96    |
| 13-2041.00 | Credit Analysts                                                                                             | 97    |
| 13-2051.00 | Financial and Investment Analysts                                                                           | 98    |
| 13-2052.00 | Personal Financial Advisors                                                                                 | 99    |
| 13-2053.00 | Insurance Underwriters                                                                                      | 100   |
| 13-2054.00 | Financial Risk Specialists                                                                                  | 101   |
| 13-2061.00 | Financial Examiners                                                                                         | 102   |
| 13-2071.00 | Credit Counselors                                                                                           | 103   |
| 13-2072.00 | Loan Officers                                                                                               | 104   |
| 13-2081.00 | Tax Examiners and Collectors, and Revenue Agents                                                            | 105   |
| 13-2082.00 | Tax Preparers                                                                                               | 106   |
| 13-2099.00 | Financial Specialists, All Other                                                                            | 107   |
| 13-2099.01 | Financial Quantitative Analysts                                                                             | 108   |
| 13-2099.04 | Fraud Examiners, Investigators and Analysts                                                                 | 109   |
| 15-1211.00 | Computer Systems Analysts                                                                                   | 110   |
| 15-1211.01 | Health Informatics Specialists                                                                              | 111   |
| 15-1212.00 | Information Security Analysts                                                                               | 112   |
| 15-1221.00 | Computer and Information Research   Scientists                                                              | 113   |
| 15-1231.00 | Computer Network Support Specialists                                                                        | 114   |
| 15-1232.00 | Computer User Support Specialists                                                                           | 115   |
| 15-1241.00 | Computer Network Architects                                                                                 | 116   |
| 15-1241.01 | Telecommunications Engineering Specialists                                                                  | 117   |
| 15-1242.00 | Database Administrators                                                                                     | 118   |
| 15-1243.00 | Database Architects                                                                                         | 119   |
| 15-1243.01 | Data Warehousing Specialists                                                                                | 120   |
| 15-1244.00 | Network and Computer Systems Administrators                                                                 | 121   |
| 15-1251.00 | Computer Programmers                                                                                        | 122   |
| 15-1252.00 | Software Developers                                                                                         | 123   |
| 15-1253.00 | Software Quality Assurance Analysts and Testers                                                             | 124   |
| 15-1254.00 | Web Developers                                                                                              | 125   |
| 15-1255.00 | Web and Digital Interface Designers                                                                         | 126   |
| 15-1255.01 | Video Game Designers                                                                                        | 127   |
| 15-1299.00 | Computer Occupations, All Other                                                                             | 128   |
| 15-1299.01 | Web Administrators                                                                                          | 129   |
| 15-1299.02 | Geographic Information Systems Technologists and Technicians                                                | 130   |
| 15-1299.03 | Document Management Specialists                                                                             | 131   |
| 15-1299.04 | Penetration Testers                                                                                         | 132   |
| 15-1299.05 | Information Security Engineers                                                                              | 133   |
| 15-1299.06 | Digital Forensics Analysts                                                                                  | 134   |
| 15-1299.07 | Blockchain Engineers                                                                                        | 135   |
| 15-1299.08 | Computer Systems Engineers/Architects                                                                       | 136   |
| 15-1299.09 | Information Technology Project Managers                                                                     | 137   |
| 15-2011.00 | Actuaries                                                                                                   | 138   |
| 15-2021.00 | Mathematicians                                                                                              | 139   |
| 15-2031.00 | Operations Research Analysts                                                                                | 140   |
| 15-2041.00 | Statisticians                                                                                               | 141   |
| 15-2041.01 | Biostatisticians                                                                                            | 142   |
| 15-2051.00 | Data Scientists                                                                                             | 143   |
| 15-2051.01 | Business Intelligence Analysts                                                                              | 144   |
| 15-2051.02 | Clinical Data Managers                                                                                      | 145   |
| 15-2099.00 | Mathematical Science Occupations, All Other                                                                 | 146   |
| 15-2099.01 | Bioinformatics Technicians                                                                                  | 147   |
| 17-1011.00 | Architects, Except Landscape and Naval                                                                      | 148   |
| 17-1012.00 | Landscape Architects                                                                                        | 149   |
| 17-1021.00 | Cartographers and Photogrammetrists                                                                         | 150   |
| 17-1022.00 | Surveyors                                                                                                   | 151   |
| 17-1022.01 | Geodetic Surveyors                                                                                          | 152   |
| 17-2011.00 | Aerospace Engineers                                                                                         | 153   |
| 17-2021.00 | Agricultural Engineers                                                                                      | 154   |
| 17-2031.00 | Bioengineers and Biomedical Engineers                                                                       | 155   |
| 17-2041.00 | Chemical Engineers                                                                                          | 156   |
| 17-2051.00 | Civil Engineers                                                                                             | 157   |
| 17-2051.01 | Transportation Engineers                                                                                    | 158   |
| 17-2051.02 | Water/Wastewater Engineers                                                                                  | 159   |
| 17-2061.00 | Computer Hardware Engineers                                                                                 | 160   |
| 17-2071.00 | Electrical Engineers                                                                                        | 161   |
| 17-2072.00 | Electronics Engineers, Except Computer                                                                      | 162   |
| 17-2072.01 | Radio Frequency Identification Device Specialists                                                           | 163   |
| 17-2081.00 | Environmental Engineers                                                                                     | 164   |
| 17-2111.00 | Health and Safety Engineers, Except Mining Safety Engineers   and Inspectors                                | 165   |
| 17-2111.02 | Fire-Prevention and Protection Engineers                                                                    | 166   |
| 17-2112.00 | Industrial Engineers                                                                                        | 167   |
| 17-2112.01 | Human Factors Engineers and Ergonomists                                                                     | 168   |
| 17-2112.02 | Validation Engineers                                                                                        | 169   |
| 17-2112.03 | Manufacturing Engineers                                                                                     | 170   |
| 17-2121.00 | Marine Engineers and Naval Architects                                                                       | 171   |
| 17-2131.00 | Materials Engineers                                                                                         | 172   |
| 17-2141.00 | Mechanical Engineers                                                                                        | 173   |
| 17-2141.01 | Fuel Cell Engineers                                                                                         | 174   |
| 17-2141.02 | Automotive Engineers                                                                                        | 175   |
| 17-2151.00 | Mining and Geological Engineers,   Including Mining Safety Engineers                                        | 176   |
| 17-2161.00 | Nuclear Engineers                                                                                           | 177   |
| 17-2171.00 | Petroleum Engineers                                                                                         | 178   |
| 17-2199.00 | Engineers, All Other                                                                                        | 179   |
| 17-2199.03 | Energy Engineers, Except Wind and Solar                                                                     | 180   |
| 17-2199.05 | Mechatronics Engineers                                                                                      | 181   |
| 17-2199.06 | Microsystems Engineers                                                                                      | 182   |
| 17-2199.07 | Photonics Engineers                                                                                         | 183   |
| 17-2199.08 | Robotics Engineers                                                                                          | 184   |
| 17-2199.09 | Nanosystems Engineers                                                                                       | 185   |
| 17-2199.10 | Wind Energy Engineers                                                                                       | 186   |
| 17-2199.11 | Solar Energy Systems Engineers                                                                              | 187   |
| 17-3011.00 | Architectural and Civil Drafters                                                                            | 188   |
| 17-3012.00 | Electrical and Electronics Drafters                                                                         | 189   |
| 17-3013.00 | Mechanical Drafters                                                                                         | 190   |
| 17-3019.00 | Drafters, All Other                                                                                         | 191   |
| 17-3021.00 | Aerospace Engineering and Operations Technologists and Technicians                                          | 192   |
| 17-3022.00 | Civil Engineering Technologists and Technicians                                                             | 193   |
| 17-3023.00 | Electrical and Electronic Engineering Technologists and Technicians                                         | 194   |
| 17-3024.00 | Electro-Mechanical and Mechatronics Technologists and Technicians                                           | 195   |
| 17-3024.01 | Robotics Technicians                                                                                        | 196   |
| 17-3025.00 | Environmental Engineering Technologists and Technicians                                                     | 197   |
| 17-3026.00 | Industrial Engineering Technologists and Technicians                                                        | 198   |
| 17-3026.01 | Nanotechnology Engineering Technologists and Technicians                                                    | 199   |
| 17-3027.00 | Mechanical Engineering Technologists and Technicians                                                        | 200   |
| 17-3027.01 | Automotive Engineering Technicians                                                                          | 201   |
| 17-3028.00 | Calibration Technologists and Technicians                                                                   | 202   |
| 17-3029.00 | Engineering Technologists and Technicians, Except Drafters, All Other                                       | 203   |
| 17-3029.01 | Non-Destructive Testing Specialists                                                                         | 204   |
| 17-3029.08 | Photonics Technicians                                                                                       | 205   |
| 17-3031.00 | Surveying and Mapping Technicians                                                                           | 206   |
| 19-1011.00 | Animal Scientists                                                                                           | 207   |
| 19-1012.00 | Food Scientists and Technologists                                                                           | 208   |
| 19-1013.00 | Soil and Plant Scientists                                                                                   | 209   |
| 19-1021.00 | Biochemists and Biophysicists                                                                               | 210   |
| 19-1022.00 | Microbiologists                                                                                             | 211   |
| 19-1023.00 | Zoologists and Wildlife Biologists                                                                          | 212   |
| 19-1029.00 | Biological Scientists, All Other                                                                            | 213   |
| 19-1029.01 | Bioinformatics Scientists                                                                                   | 214   |
| 19-1029.02 | Molecular and Cellular Biologists                                                                           | 215   |
| 19-1029.03 | Geneticists                                                                                                 | 216   |
| 19-1029.04 | Biologists                                                                                                  | 217   |
| 19-1031.00 | Conservation Scientists                                                                                     | 218   |
| 19-1031.02 | Range Managers                                                                                              | 219   |
| 19-1031.03 | Park Naturalists                                                                                            | 220   |
| 19-1032.00 | Foresters                                                                                                   | 221   |
| 19-1041.00 | Epidemiologists                                                                                             | 222   |
| 19-1042.00 | Medical Scientists, Except Epidemiologists                                                                  | 223   |
| 19-1099.00 | Life Scientists, All Other                                                                                  | 224   |
| 19-2011.00 | Astronomers                                                                                                 | 225   |
| 19-2012.00 | Physicists                                                                                                  | 226   |
| 19-2021.00 | Atmospheric and Space Scientists                                                                            | 227   |
| 19-2031.00 | Chemists                                                                                                    | 228   |
| 19-2032.00 | Materials Scientists                                                                                        | 229   |
| 19-2041.00 | Environmental Scientists and Specialists, Including Health                                                  | 230   |
| 19-2041.01 | Climate Change Policy Analysts                                                                              | 231   |
| 19-2041.02 | Environmental Restoration Planners                                                                          | 232   |
| 19-2041.03 | Industrial Ecologists                                                                                       | 233   |
| 19-2042.00 | Geoscientists, Except Hydrologists and Geographers                                                          | 234   |
| 19-2043.00 | Hydrologists                                                                                                | 235   |
| 19-2099.00 | Physical Scientists, All Other                                                                              | 236   |
| 19-2099.01 | Remote Sensing Scientists and Technologists                                                                 | 237   |
| 19-3011.00 | Economists                                                                                                  | 238   |
| 19-3011.01 | Environmental Economists                                                                                    | 239   |
| 19-3022.00 | Survey Researchers                                                                                          | 240   |
| 19-3032.00 | Industrial-Organizational Psychologists                                                                     | 241   |
| 19-3033.00 | Clinical and Counseling Psychologists                                                                       | 242   |
| 19-3034.00 | School Psychologists                                                                                        | 243   |
| 19-3039.00 | Psychologists, All Other                                                                                    | 244   |
| 19-3039.02 | Neuropsychologists                                                                                          | 245   |
| 19-3039.03 | Clinical Neuropsychologists                                                                                 | 246   |
| 19-3041.00 | Sociologists                                                                                                | 247   |
| 19-3051.00 | Urban and Regional Planners                                                                                 | 248   |
| 19-3091.00 | Anthropologists and Archeologists                                                                           | 249   |
| 19-3092.00 | Geographers                                                                                                 | 250   |
| 19-3093.00 | Historians                                                                                                  | 251   |
| 19-3094.00 | Political Scientists                                                                                        | 252   |
| 19-3099.00 | Social Scientists and Related Workers, All Other                                                            | 253   |
| 19-3099.01 | Transportation Planners                                                                                     | 254   |
| 19-4012.00 | Agricultural Technicians                                                                                    | 255   |
| 19-4012.01 | Precision Agriculture Technicians                                                                           | 256   |
| 19-4013.00 | Food Science Technicians                                                                                    | 257   |
| 19-4021.00 | Biological Technicians                                                                                      | 258   |
| 19-4031.00 | Chemical Technicians                                                                                        | 259   |
| 19-4042.00 | Environmental Science and Protection Technicians, Including Health                                          | 260   |
| 19-4043.00 | Geological Technicians, Except Hydrologic Technicians                                                       | 261   |
| 19-4044.00 | Hydrologic Technicians                                                                                      | 262   |
| 19-4051.00 | Nuclear Technicians                                                                                         | 263   |
| 19-4051.02 | Nuclear Monitoring Technicians                                                                              | 264   |
| 19-4061.00 | Social Science Research Assistants                                                                          | 265   |
| 19-4071.00 | Forest and Conservation Technicians                                                                         | 266   |
| 19-4092.00 | Forensic Science Technicians                                                                                | 267   |
| 19-4099.00 | Life, Physical, and Social Science Technicians, All Other                                                   | 268   |
| 19-4099.01 | Quality Control Analysts                                                                                    | 269   |
| 19-4099.03 | Remote Sensing Technicians                                                                                  | 270   |
| 19-5011.00 | Occupational Health and Safety Specialists                                                                  | 271   |
| 19-5012.00 | Occupational Health and Safety Technicians                                                                  | 272   |
| 21-1011.00 | Substance Abuse and Behavioral Disorder Counselors                                                          | 273   |
| 21-1012.00 | Educational, Guidance, and Career Counselors and Advisors                                                   | 274   |
| 21-1013.00 | Marriage and Family Therapists                                                                              | 275   |
| 21-1014.00 | Mental Health Counselors                                                                                    | 276   |
| 21-1015.00 | Rehabilitation Counselors                                                                                   | 277   |
| 21-1019.00 | Counselors, All Other                                                                                       | 278   |
| 21-1021.00 | Child, Family, and School Social Workers                                                                    | 279   |
| 21-1022.00 | Healthcare Social Workers                                                                                   | 280   |
| 21-1023.00 | Mental Health and Substance Abuse Social Workers                                                            | 281   |
| 21-1029.00 | Social Workers, All Other                                                                                   | 282   |
| 21-1091.00 | Health Education Specialists                                                                                | 283   |
| 21-1092.00 | Probation Officers and Correctional Treatment Specialists                                                   | 284   |
| 21-1093.00 | Social and Human Service Assistants                                                                         | 285   |
| 21-1094.00 | Community Health Workers                                                                                    | 286   |
| 21-1099.00 | Community and Social Service Specialists, All Other                                                         | 287   |
| 21-2011.00 | Clergy                                                                                                      | 288   |
| 21-2021.00 | Directors, Religious Activities and   Education                                                             | 289   |
| 21-2099.00 | Religious Workers, All Other                                                                                | 290   |
| 23-1011.00 | Lawyers                                                                                                     | 291   |
| 23-1012.00 | Judicial Law Clerks                                                                                         | 292   |
| 23-1021.00 | Administrative Law Judges, Adjudicators, and Hearing Officers                                               | 293   |
| 23-1022.00 | Arbitrators, Mediators, and Conciliators                                                                    | 294   |
| 23-1023.00 | Judges, Magistrate Judges, and Magistrates                                                                  | 295   |
| 23-2011.00 | Paralegals and Legal Assistants                                                                             | 296   |
| 23-2093.00 | Title Examiners, Abstractors, and Searchers                                                                 | 297   |
| 23-2099.00 | Legal Support Workers, All Other                                                                            | 298   |
| 25-1011.00 | Business Teachers, Postsecondary                                                                            | 299   |
| 25-1021.00 | Computer Science Teachers, Postsecondary                                                                    | 300   |
| 25-1022.00 | Mathematical Science Teachers, Postsecondary                                                                | 301   |
| 25-1031.00 | Architecture Teachers, Postsecondary                                                                        | 302   |
| 25-1032.00 | Engineering Teachers, Postsecondary                                                                         | 303   |
| 25-1041.00 | Agricultural Sciences Teachers, Postsecondary                                                               | 304   |
| 25-1042.00 | Biological Science Teachers, Postsecondary                                                                  | 305   |
| 25-1043.00 | Forestry and Conservation Science Teachers, Postsecondary                                                   | 306   |
| 25-1051.00 | Atmospheric, Earth, Marine, and Space Sciences Teachers,   Postsecondary                                    | 307   |
| 25-1052.00 | Chemistry Teachers, Postsecondary                                                                           | 308   |
| 25-1053.00 | Environmental Science Teachers, Postsecondary                                                               | 309   |
| 25-1054.00 | Physics Teachers, Postsecondary                                                                             | 310   |
| 25-1061.00 | Anthropology and Archeology Teachers, Postsecondary                                                         | 311   |
| 25-1062.00 | Area, Ethnic, and Cultural Studies Teachers, Postsecondary                                                  | 312   |
| 25-1063.00 | Economics Teachers, Postsecondary                                                                           | 313   |
| 25-1064.00 | Geography Teachers, Postsecondary                                                                           | 314   |
| 25-1065.00 | Political Science Teachers, Postsecondary                                                                   | 315   |
| 25-1066.00 | Psychology Teachers, Postsecondary                                                                          | 316   |
| 25-1067.00 | Sociology Teachers, Postsecondary                                                                           | 317   |
| 25-1069.00 | Social Sciences Teachers, Postsecondary, All Other                                                          | 318   |
| 25-1071.00 | Health Specialties Teachers, Postsecondary                                                                  | 319   |
| 25-1072.00 | Nursing Instructors and Teachers, Postsecondary                                                             | 320   |
| 25-1081.00 | Education Teachers, Postsecondary                                                                           | 321   |
| 25-1082.00 | Library Science Teachers, Postsecondary                                                                     | 322   |
| 25-1111.00 | Criminal Justice and Law Enforcement Teachers, Postsecondary                                                | 323   |
| 25-1112.00 | Law Teachers, Postsecondary                                                                                 | 324   |
| 25-1113.00 | Social Work Teachers, Postsecondary                                                                         | 325   |
| 25-1121.00 | Art, Drama, and Music Teachers, Postsecondary                                                               | 326   |
| 25-1122.00 | Communications Teachers, Postsecondary                                                                      | 327   |
| 25-1123.00 | English Language and Literature Teachers, Postsecondary                                                     | 328   |
| 25-1124.00 | Foreign Language and Literature Teachers, Postsecondary                                                     | 329   |
| 25-1125.00 | History Teachers, Postsecondary                                                                             | 330   |
| 25-1126.00 | Philosophy and Religion Teachers, Postsecondary                                                             | 331   |
| 25-1192.00 | Family and Consumer Sciences Teachers, Postsecondary                                                        | 332   |
| 25-1193.00 | Recreation and Fitness Studies Teachers, Postsecondary                                                      | 333   |
| 25-1194.00 | Career/Technical Education Teachers, Postsecondary                                                          | 334   |
| 25-1199.00 | Postsecondary Teachers, All Other                                                                           | 335   |
| 25-2011.00 | Preschool Teachers, Except Special Education                                                                | 336   |
| 25-2012.00 | Kindergarten Teachers, Except Special Education                                                             | 337   |
| 25-2021.00 | Elementary School Teachers, Except Special Education                                                        | 338   |
| 25-2022.00 | Middle School Teachers, Except Special and Career/Technical   Education                                     | 339   |
| 25-2023.00 | Career/Technical Education Teachers, Middle School                                                          | 340   |
| 25-2031.00 | Secondary School Teachers, Except Special and Career/Technical   Education                                  | 341   |
| 25-2032.00 | Career/Technical Education Teachers, Secondary School                                                       | 342   |
| 25-2051.00 | Special Education Teachers, Preschool                                                                       | 343   |
| 25-2055.00 | Special Education Teachers, Kindergarten                                                                    | 344   |
| 25-2056.00 | Special Education Teachers, Elementary School                                                               | 345   |
| 25-2057.00 | Special Education Teachers, Middle School                                                                   | 346   |
| 25-2058.00 | Special Education Teachers, Secondary School                                                                | 347   |
| 25-2059.00 | Special Education Teachers, All Other                                                                       | 348   |
| 25-2059.01 | Adapted Physical Education Specialists                                                                      | 349   |
| 25-3011.00 | Adult Basic Education, Adult Secondary Education, and English   as a Second Language Instructors            | 350   |
| 25-3021.00 | Self-Enrichment Teachers                                                                                    | 351   |
| 25-3031.00 | Substitute Teachers, Short-Term                                                                             | 352   |
| 25-3041.00 | Tutors                                                                                                      | 353   |
| 25-3099.00 | Teachers and Instructors, All Other                                                                         | 354   |
| 25-4011.00 | Archivists                                                                                                  | 355   |
| 25-4012.00 | Curators                                                                                                    | 356   |
| 25-4013.00 | Museum Technicians and Conservators                                                                         | 357   |
| 25-4022.00 | Librarians and Media Collections   Specialists                                                              | 358   |
| 25-4031.00 | Library Technicians                                                                                         | 359   |
| 25-9021.00 | Farm and Home Management Educators                                                                          | 360   |
| 25-9031.00 | Instructional Coordinators                                                                                  | 361   |
| 25-9042.00 | Teaching Assistants, Preschool, Elementary, Middle, and   Secondary School, Except Special Education        | 362   |
| 25-9043.00 | Teaching Assistants, Special Education                                                                      | 363   |
| 25-9044.00 | Teaching Assistants, Postsecondary                                                                          | 364   |
| 25-9049.00 | Teaching Assistants, All Other                                                                              | 365   |
| 25-9099.00 | Educational Instruction and Library Workers, All Other                                                      | 366   |
| 27-1011.00 | Art Directors                                                                                               | 367   |
| 27-1012.00 | Craft Artists                                                                                               | 368   |
| 27-1013.00 | Fine Artists, Including Painters, Sculptors, and Illustrators                                               | 369   |
| 27-1014.00 | Special Effects Artists and Animators                                                                       | 370   |
| 27-1019.00 | Artists and Related Workers, All Other                                                                      | 371   |
| 27-1021.00 | Commercial and Industrial Designers                                                                         | 372   |
| 27-1022.00 | Fashion Designers                                                                                           | 373   |
| 27-1023.00 | Floral Designers                                                                                            | 374   |
| 27-1024.00 | Graphic Designers                                                                                           | 375   |
| 27-1025.00 | Interior Designers                                                                                          | 376   |
| 27-1026.00 | Merchandise Displayers and Window Trimmers                                                                  | 377   |
| 27-1027.00 | Set and Exhibit Designers                                                                                   | 378   |
| 27-1029.00 | Designers, All Other                                                                                        | 379   |
| 27-2011.00 | Actors                                                                                                      | 380   |
| 27-2012.00 | Producers and Directors                                                                                     | 381   |
| 27-2012.03 | Media Programming Directors                                                                                 | 382   |
| 27-2012.04 | Talent Directors                                                                                            | 383   |
| 27-2012.05 | Media Technical Directors/Managers                                                                          | 384   |
| 27-2021.00 | Athletes and Sports Competitors                                                                             | 385   |
| 27-2022.00 | Coaches and Scouts                                                                                          | 386   |
| 27-2023.00 | Umpires, Referees, and Other Sports Officials                                                               | 387   |
| 27-2031.00 | Dancers                                                                                                     | 388   |
| 27-2032.00 | Choreographers                                                                                              | 389   |
| 27-2041.00 | Music Directors and Composers                                                                               | 390   |
| 27-2042.00 | Musicians and Singers                                                                                       | 391   |
| 27-2091.00 | Disc Jockeys, Except Radio                                                                                  | 392   |
| 27-2099.00 | Entertainers and Performers, Sports and Related Workers, All   Other                                        | 393   |
| 27-3011.00 | Broadcast Announcers and Radio Disc   Jockeys                                                               | 394   |
| 27-3023.00 | News Analysts, Reporters, and   Journalists                                                                 | 395   |
| 27-3031.00 | Public Relations Specialists                                                                                | 396   |
| 27-3041.00 | Editors                                                                                                     | 397   |
| 27-3042.00 | Technical Writers                                                                                           | 398   |
| 27-3043.00 | Writers and Authors                                                                                         | 399   |
| 27-3043.05 | Poets, Lyricists and Creative Writers                                                                       | 400   |
| 27-3091.00 | Interpreters and Translators                                                                                | 401   |
| 27-3092.00 | Court Reporters and Simultaneous Captioners                                                                 | 402   |
| 27-3099.00 | Media and Communication Workers, All Other                                                                  | 403   |
| 27-4011.00 | Audio and Video Technicians                                                                                 | 404   |
| 27-4012.00 | Broadcast Technicians                                                                                       | 405   |
| 27-4014.00 | Sound Engineering Technicians                                                                               | 406   |
| 27-4015.00 | Lighting Technicians                                                                                        | 407   |
| 27-4021.00 | Photographers                                                                                               | 408   |
| 27-4031.00 | Camera Operators, Television, Video, and Film                                                               | 409   |
| 27-4032.00 | Film and Video Editors                                                                                      | 410   |
| 27-4099.00 | Media and Communication Equipment Workers, All Other                                                        | 411   |
| 29-1011.00 | Chiropractors                                                                                               | 412   |
| 29-1021.00 | Dentists, General                                                                                           | 413   |
| 29-1022.00 | Oral and Maxillofacial Surgeons                                                                             | 414   |
| 29-1023.00 | Orthodontists                                                                                               | 415   |
| 29-1024.00 | Prosthodontists                                                                                             | 416   |
| 29-1029.00 | Dentists, All Other Specialists                                                                             | 417   |
| 29-1031.00 | Dietitians and Nutritionists                                                                                | 418   |
| 29-1041.00 | Optometrists                                                                                                | 419   |
| 29-1051.00 | Pharmacists                                                                                                 | 420   |
| 29-1071.00 | Physician Assistants                                                                                        | 421   |
| 29-1071.01 | Anesthesiologist Assistants                                                                                 | 422   |
| 29-1081.00 | Podiatrists                                                                                                 | 423   |
| 29-1122.00 | Occupational Therapists                                                                                     | 424   |
| 29-1122.01 | Low Vision Therapists, Orientation and Mobility Specialists,   and Vision Rehabilitation Therapists         | 425   |
| 29-1123.00 | Physical Therapists                                                                                         | 426   |
| 29-1124.00 | Radiation Therapists                                                                                        | 427   |
| 29-1125.00 | Recreational Therapists                                                                                     | 428   |
| 29-1126.00 | Respiratory Therapists                                                                                      | 429   |
| 29-1127.00 | Speech-Language Pathologists                                                                                | 430   |
| 29-1128.00 | Exercise Physiologists                                                                                      | 431   |
| 29-1129.00 | Therapists, All Other                                                                                       | 432   |
| 29-1129.01 | Art Therapists                                                                                              | 433   |
| 29-1129.02 | Music Therapists                                                                                            | 434   |
| 29-1131.00 | Veterinarians                                                                                               | 435   |
| 29-1141.00 | Registered Nurses                                                                                           | 436   |
| 29-1141.01 | Acute Care Nurses                                                                                           | 437   |
| 29-1141.02 | Advanced Practice Psychiatric Nurses                                                                        | 438   |
| 29-1141.03 | Critical Care Nurses                                                                                        | 439   |
| 29-1141.04 | Clinical Nurse Specialists                                                                                  | 440   |
| 29-1151.00 | Nurse Anesthetists                                                                                          | 441   |
| 29-1161.00 | Nurse Midwives                                                                                              | 442   |
| 29-1171.00 | Nurse Practitioners                                                                                         | 443   |
| 29-1181.00 | Audiologists                                                                                                | 444   |
| 29-1211.00 | Anesthesiologists                                                                                           | 445   |
| 29-1212.00 | Cardiologists                                                                                               | 446   |
| 29-1213.00 | Dermatologists                                                                                              | 447   |
| 29-1214.00 | Emergency Medicine Physicians                                                                               | 448   |
| 29-1215.00 | Family Medicine Physicians                                                                                  | 449   |
| 29-1216.00 | General Internal Medicine Physicians                                                                        | 450   |
| 29-1217.00 | Neurologists                                                                                                | 451   |
| 29-1218.00 | Obstetricians and Gynecologists                                                                             | 452   |
| 29-1221.00 | Pediatricians, General                                                                                      | 453   |
| 29-1222.00 | Physicians, Pathologists                                                                                    | 454   |
| 29-1223.00 | Psychiatrists                                                                                               | 455   |
| 29-1224.00 | Radiologists                                                                                                | 456   |
| 29-1229.00 | Physicians, All Other                                                                                       | 457   |
| 29-1229.01 | Allergists and Immunologists                                                                                | 458   |
| 29-1229.02 | Hospitalists                                                                                                | 459   |
| 29-1229.03 | Urologists                                                                                                  | 460   |
| 29-1229.04 | Physical Medicine and Rehabilitation Physicians                                                             | 461   |
| 29-1229.05 | Preventive Medicine Physicians                                                                              | 462   |
| 29-1229.06 | Sports Medicine Physicians                                                                                  | 463   |
| 29-1241.00 | Ophthalmologists, Except Pediatric                                                                          | 464   |
| 29-1242.00 | Orthopedic Surgeons, Except Pediatric                                                                       | 465   |
| 29-1243.00 | Pediatric Surgeons                                                                                          | 466   |
| 29-1249.00 | Surgeons, All Other                                                                                         | 467   |
| 29-1291.00 | Acupuncturists                                                                                              | 468   |
| 29-1292.00 | Dental Hygienists                                                                                           | 469   |
| 29-1299.00 | Healthcare Diagnosing or Treating Practitioners, All Other                                                  | 470   |
| 29-1299.01 | Naturopathic Physicians                                                                                     | 471   |
| 29-1299.02 | Orthoptists                                                                                                 | 472   |
| 29-2011.00 | Medical and Clinical Laboratory Technologists                                                               | 473   |
| 29-2011.01 | Cytogenetic Technologists                                                                                   | 474   |
| 29-2011.02 | Cytotechnologists                                                                                           | 475   |
| 29-2011.04 | Histotechnologists                                                                                          | 476   |
| 29-2012.00 | Medical and Clinical Laboratory Technicians                                                                 | 477   |
| 29-2012.01 | Histology Technicians                                                                                       | 478   |
| 29-2031.00 | Cardiovascular Technologists and Technicians                                                                | 479   |
| 29-2032.00 | Diagnostic Medical Sonographers                                                                             | 480   |
| 29-2033.00 | Nuclear Medicine Technologists                                                                              | 481   |
| 29-2034.00 | Radiologic Technologists and Technicians                                                                    | 482   |
| 29-2035.00 | Magnetic Resonance Imaging Technologists                                                                    | 483   |
| 29-2036.00 | Medical Dosimetrists                                                                                        | 484   |
| 29-2042.00 | Emergency Medical Technicians                                                                               | 485   |
| 29-2043.00 | Paramedics                                                                                                  | 486   |
| 29-2051.00 | Dietetic Technicians                                                                                        | 487   |
| 29-2052.00 | Pharmacy Technicians                                                                                        | 488   |
| 29-2053.00 | Psychiatric Technicians                                                                                     | 489   |
| 29-2055.00 | Surgical Technologists                                                                                      | 490   |
| 29-2056.00 | Veterinary Technologists and Technicians                                                                    | 491   |
| 29-2057.00 | Ophthalmic Medical Technicians                                                                              | 492   |
| 29-2061.00 | Licensed Practical and Licensed   Vocational Nurses                                                         | 493   |
| 29-2072.00 | Medical Records Specialists                                                                                 | 494   |
| 29-2081.00 | Opticians, Dispensing                                                                                       | 495   |
| 29-2091.00 | Orthotists and Prosthetists                                                                                 | 496   |
| 29-2092.00 | Hearing Aid Specialists                                                                                     | 497   |
| 29-2099.00 | Health Technologists and Technicians, All Other                                                             | 498   |
| 29-2099.01 | Neurodiagnostic Technologists                                                                               | 499   |
| 29-2099.05 | Ophthalmic Medical Technologists                                                                            | 500   |
| 29-2099.08 | Patient Representatives                                                                                     | 501   |
| 29-9021.00 | Health Information Technologists and   Medical Registrars                                                   | 502   |
| 29-9091.00 | Athletic Trainers                                                                                           | 503   |
| 29-9092.00 | Genetic Counselors                                                                                          | 504   |
| 29-9093.00 | Surgical Assistants                                                                                         | 505   |
| 29-9099.00 | Healthcare Practitioners and Technical Workers, All Other                                                   | 506   |
| 29-9099.01 | Midwives                                                                                                    | 507   |
| 31-1121.00 | Home Health Aides                                                                                           | 508   |
| 31-1122.00 | Personal Care Aides                                                                                         | 509   |
| 31-1131.00 | Nursing Assistants                                                                                          | 510   |
| 31-1132.00 | Orderlies                                                                                                   | 511   |
| 31-1133.00 | Psychiatric Aides                                                                                           | 512   |
| 31-2011.00 | Occupational Therapy Assistants                                                                             | 513   |
| 31-2012.00 | Occupational Therapy Aides                                                                                  | 514   |
| 31-2021.00 | Physical Therapist Assistants                                                                               | 515   |
| 31-2022.00 | Physical Therapist Aides                                                                                    | 516   |
| 31-9011.00 | Massage Therapists                                                                                          | 517   |
| 31-9091.00 | Dental Assistants                                                                                           | 518   |
| 31-9092.00 | Medical Assistants                                                                                          | 519   |
| 31-9093.00 | Medical Equipment Preparers                                                                                 | 520   |
| 31-9094.00 | Medical Transcriptionists                                                                                   | 521   |
| 31-9095.00 | Pharmacy Aides                                                                                              | 522   |
| 31-9096.00 | Veterinary Assistants and Laboratory Animal Caretakers                                                      | 523   |
| 31-9097.00 | Phlebotomists                                                                                               | 524   |
| 31-9099.00 | Healthcare Support Workers, All Other                                                                       | 525   |
| 31-9099.01 | Speech-Language Pathology Assistants                                                                        | 526   |
| 31-9099.02 | Endoscopy Technicians                                                                                       | 527   |
| 33-1011.00 | First-Line Supervisors of Correctional Officers                                                             | 528   |
| 33-1012.00 | First-Line Supervisors of Police and Detectives                                                             | 529   |
| 33-1021.00 | First-Line Supervisors of Firefighting   and Prevention Workers                                             | 530   |
| 33-1091.00 | First-Line Supervisors of Security Workers                                                                  | 531   |
| 33-1099.00 | First-Line Supervisors of Protective Service Workers, All   Other                                           | 532   |
| 33-2011.00 | Firefighters                                                                                                | 533   |
| 33-2021.00 | Fire Inspectors and Investigators                                                                           | 534   |
| 33-2022.00 | Forest Fire Inspectors and Prevention Specialists                                                           | 535   |
| 33-3011.00 | Bailiffs                                                                                                    | 536   |
| 33-3012.00 | Correctional Officers and Jailers                                                                           | 537   |
| 33-3021.00 | Detectives and Criminal Investigators                                                                       | 538   |
| 33-3021.02 | Police Identification and Records Officers                                                                  | 539   |
| 33-3021.06 | Intelligence Analysts                                                                                       | 540   |
| 33-3031.00 | Fish and Game Wardens                                                                                       | 541   |
| 33-3041.00 | Parking Enforcement Workers                                                                                 | 542   |
| 33-3051.00 | Police and Sheriff's Patrol Officers                                                                        | 543   |
| 33-3051.04 | Customs and Border Protection Officers                                                                      | 544   |
| 33-3052.00 | Transit and Railroad Police                                                                                 | 545   |
| 33-9011.00 | Animal Control Workers                                                                                      | 546   |
| 33-9021.00 | Private Detectives and Investigators                                                                        | 547   |
| 33-9031.00 | Gambling Surveillance Officers and Gambling Investigators                                                   | 548   |
| 33-9032.00 | Security Guards                                                                                             | 549   |
| 33-9091.00 | Crossing Guards and Flaggers                                                                                | 550   |
| 33-9092.00 | Lifeguards, Ski Patrol, and Other Recreational Protective Service Workers                                   | 551   |
| 33-9093.00 | Transportation Security Screeners                                                                           | 552   |
| 33-9094.00 | School Bus Monitors                                                                                         | 553   |
| 33-9099.00 | Protective Service Workers, All Other                                                                       | 554   |
| 33-9099.02 | Retail Loss Prevention Specialists                                                                          | 555   |
| 35-1011.00 | Chefs and Head Cooks                                                                                        | 556   |
| 35-1012.00 | First-Line Supervisors of Food Preparation and Serving Workers                                              | 557   |
| 35-2011.00 | Cooks, Fast Food                                                                                            | 558   |
| 35-2012.00 | Cooks, Institution and Cafeteria                                                                            | 559   |
| 35-2013.00 | Cooks, Private Household                                                                                    | 560   |
| 35-2014.00 | Cooks, Restaurant                                                                                           | 561   |
| 35-2015.00 | Cooks, Short Order                                                                                          | 562   |
| 35-2019.00 | Cooks, All Other                                                                                            | 563   |
| 35-2021.00 | Food Preparation Workers                                                                                    | 564   |
| 35-3011.00 | Bartenders                                                                                                  | 565   |
| 35-3021.00 | Combined food preparation and serving workers, including fast   food                                        | 1017  |
| 35-3023.00 | Fast Food and Counter Workers                                                                               | 566   |
| 35-3023.01 | Baristas                                                                                                    | 567   |
| 35-3031.00 | Waiters and Waitresses                                                                                      | 568   |
| 35-3041.00 | Food Servers, Nonrestaurant                                                                                 | 569   |
| 35-9011.00 | Dining Room and Cafeteria Attendants and Bartender Helpers                                                  | 570   |
| 35-9021.00 | Dishwashers                                                                                                 | 571   |
| 35-9031.00 | Hosts and Hostesses, Restaurant, Lounge, and Coffee Shop                                                    | 572   |
| 35-9099.00 | Food Preparation and Serving Related Workers, All Other                                                     | 573   |
| 37-1011.00 | First-Line Supervisors of Housekeeping and Janitorial Workers                                               | 574   |
| 37-1012.00 | First-Line Supervisors of Landscaping, Lawn Service, and   Groundskeeping Workers                           | 575   |
| 37-2011.00 | Janitors and Cleaners, Except Maids and Housekeeping Cleaners                                               | 576   |
| 37-2012.00 | Maids and Housekeeping Cleaners                                                                             | 577   |
| 37-2019.00 | Building Cleaning Workers, All Other                                                                        | 578   |
| 37-2021.00 | Pest Control Workers                                                                                        | 579   |
| 37-3011.00 | Landscaping and Groundskeeping Workers                                                                      | 580   |
| 37-3012.00 | Pesticide Handlers, Sprayers, and Applicators, Vegetation                                                   | 581   |
| 37-3013.00 | Tree Trimmers and Pruners                                                                                   | 582   |
| 37-3019.00 | Grounds Maintenance Workers, All Other                                                                      | 583   |
| 39-1013.00 | First-Line Supervisors of Gambling Services Workers                                                         | 584   |
| 39-1014.00 | First-Line Supervisors of Entertainment and Recreation   Workers, Except Gambling Services                  | 585   |
| 39-1022.00 | First-Line Supervisors of Personal Service Workers                                                          | 586   |
| 39-2011.00 | Animal Trainers                                                                                             | 587   |
| 39-2021.00 | Animal Caretakers                                                                                           | 588   |
| 39-3011.00 | Gambling Dealers                                                                                            | 589   |
| 39-3012.00 | Gambling and Sports Book Writers and Runners                                                                | 590   |
| 39-3019.00 | Gambling Service Workers, All Other                                                                         | 591   |
| 39-3021.00 | Motion Picture Projectionists                                                                               | 592   |
| 39-3031.00 | Ushers, Lobby Attendants, and Ticket   Takers                                                               | 593   |
| 39-3091.00 | Amusement and Recreation Attendants                                                                         | 594   |
| 39-3092.00 | Costume Attendants                                                                                          | 595   |
| 39-3093.00 | Locker Room, Coatroom, and Dressing Room Attendants                                                         | 596   |
| 39-3099.00 | Entertainment Attendants and Related Workers, All Other                                                     | 597   |
| 39-4011.00 | Embalmers                                                                                                   | 598   |
| 39-4012.00 | Crematory Operators                                                                                         | 599   |
| 39-4021.00 | Funeral Attendants                                                                                          | 600   |
| 39-4031.00 | Morticians, Undertakers, and Funeral Arrangers                                                              | 601   |
| 39-5011.00 | Barbers                                                                                                     | 602   |
| 39-5012.00 | Hairdressers, Hairstylists, and   Cosmetologists                                                            | 603   |
| 39-5091.00 | Makeup Artists, Theatrical and Performance                                                                  | 604   |
| 39-5092.00 | Manicurists and Pedicurists                                                                                 | 605   |
| 39-5093.00 | Shampooers                                                                                                  | 606   |
| 39-5094.00 | Skincare Specialists                                                                                        | 607   |
| 39-6011.00 | Baggage Porters and Bellhops                                                                                | 608   |
| 39-6012.00 | Concierges                                                                                                  | 609   |
| 39-7011.00 | Tour Guides and Escorts                                                                                     | 610   |
| 39-7012.00 | Travel Guides                                                                                               | 611   |
| 39-9011.00 | Childcare Workers                                                                                           | 612   |
| 39-9011.01 | Nannies                                                                                                     | 613   |
| 39-9021.00 | Personal care aides                                                                                         | 1018  |
| 39-9031.00 | Exercise Trainers and Group Fitness Instructors                                                             | 614   |
| 39-9032.00 | Recreation Workers                                                                                          | 615   |
| 39-9041.00 | Residential Advisors                                                                                        | 616   |
| 39-9099.00 | Personal Care and Service Workers, All Other                                                                | 617   |
| 41-1011.00 | First-Line Supervisors of Retail Sales Workers                                                              | 618   |
| 41-1012.00 | First-Line Supervisors of Non-Retail Sales Workers                                                          | 619   |
| 41-2011.00 | Cashiers                                                                                                    | 620   |
| 41-2012.00 | Gambling Change Persons and Booth Cashiers                                                                  | 621   |
| 41-2021.00 | Counter and Rental Clerks                                                                                   | 622   |
| 41-2022.00 | Parts Salespersons                                                                                          | 623   |
| 41-2031.00 | Retail Salespersons                                                                                         | 624   |
| 41-3011.00 | Advertising Sales Agents                                                                                    | 625   |
| 41-3021.00 | Insurance Sales Agents                                                                                      | 626   |
| 41-3031.00 | Securities, Commodities, and Financial Services Sales Agents                                                | 627   |
| 41-3041.00 | Travel Agents                                                                                               | 628   |
| 41-3091.00 | Sales Representatives of Services, Except Advertising,   Insurance, Financial Services, and Travel          | 629   |
| 41-4011.00 | Sales Representatives, Wholesale and Manufacturing, Technical   and Scientific Products                     | 630   |
| 41-4011.07 | Solar Sales Representatives and Assessors                                                                   | 631   |
| 41-4012.00 | Sales Representatives, Wholesale and   Manufacturing, Except Technical and Scientific Products              | 632   |
| 41-9011.00 | Demonstrators and Product Promoters                                                                         | 633   |
| 41-9012.00 | Models                                                                                                      | 634   |
| 41-9021.00 | Real Estate Brokers                                                                                         | 635   |
| 41-9022.00 | Real Estate Sales Agents                                                                                    | 636   |
| 41-9031.00 | Sales Engineers                                                                                             | 637   |
| 41-9041.00 | Telemarketers                                                                                               | 638   |
| 41-9091.00 | Door-to-Door Sales Workers, News and Street Vendors, and   Related Workers                                  | 639   |
| 41-9099.00 | Sales and Related Workers, All Other                                                                        | 640   |
| 43-1011.00 | First-Line Supervisors of Office and   Administrative Support Workers                                       | 641   |
| 43-2011.00 | Switchboard Operators, Including Answering Service                                                          | 642   |
| 43-2021.00 | Telephone Operators                                                                                         | 643   |
| 43-2099.00 | Communications Equipment Operators, All Other                                                               | 644   |
| 43-3011.00 | Bill and Account Collectors                                                                                 | 645   |
| 43-3021.00 | Billing and Posting Clerks                                                                                  | 646   |
| 43-3031.00 | Bookkeeping, Accounting, and Auditing Clerks                                                                | 647   |
| 43-3041.00 | Gambling Cage Workers                                                                                       | 648   |
| 43-3051.00 | Payroll and Timekeeping Clerks                                                                              | 649   |
| 43-3061.00 | Procurement Clerks                                                                                          | 650   |
| 43-3071.00 | Tellers                                                                                                     | 651   |
| 43-3099.00 | Financial Clerks, All Other                                                                                 | 652   |
| 43-4011.00 | Brokerage Clerks                                                                                            | 653   |
| 43-4021.00 | Correspondence Clerks                                                                                       | 654   |
| 43-4031.00 | Court, Municipal, and License Clerks                                                                        | 655   |
| 43-4041.00 | Credit Authorizers, Checkers, and Clerks                                                                    | 656   |
| 43-4051.00 | Customer Service Representatives                                                                            | 657   |
| 43-4061.00 | Eligibility Interviewers, Government Programs                                                               | 658   |
| 43-4071.00 | File Clerks                                                                                                 | 659   |
| 43-4081.00 | Hotel, Motel, and Resort Desk Clerks                                                                        | 660   |
| 43-4111.00 | Interviewers, Except Eligibility and Loan                                                                   | 661   |
| 43-4121.00 | Library Assistants, Clerical                                                                                | 662   |
| 43-4131.00 | Loan Interviewers and Clerks                                                                                | 663   |
| 43-4141.00 | New Accounts Clerks                                                                                         | 664   |
| 43-4151.00 | Order Clerks                                                                                                | 665   |
| 43-4161.00 | Human Resources Assistants, Except Payroll and Timekeeping                                                  | 666   |
| 43-4171.00 | Receptionists and Information Clerks                                                                        | 667   |
| 43-4181.00 | Reservation and Transportation Ticket Agents and Travel Clerks                                              | 668   |
| 43-4199.00 | Information and Record Clerks, All Other                                                                    | 669   |
| 43-5011.00 | Cargo and Freight Agents                                                                                    | 670   |
| 43-5011.01 | Freight Forwarders                                                                                          | 671   |
| 43-5021.00 | Couriers and Messengers                                                                                     | 672   |
| 43-5031.00 | Public Safety Telecommunicators                                                                             | 673   |
| 43-5032.00 | Dispatchers, Except Police, Fire, and Ambulance                                                             | 674   |
| 43-5041.00 | Meter Readers, Utilities                                                                                    | 675   |
| 43-5051.00 | Postal Service Clerks                                                                                       | 676   |
| 43-5052.00 | Postal Service Mail Carriers                                                                                | 677   |
| 43-5053.00 | Postal Service Mail Sorters, Processors, and Processing   Machine Operators                                 | 678   |
| 43-5061.00 | Production, Planning, and Expediting   Clerks                                                               | 679   |
| 43-5071.00 | Shipping, Receiving, and Inventory   Clerks                                                                 | 680   |
| 43-5111.00 | Weighers, Measurers, Checkers, and Samplers, Recordkeeping                                                  | 681   |
| 43-6011.00 | Executive Secretaries and Executive Administrative Assistants                                               | 682   |
| 43-6012.00 | Legal Secretaries and Administrative Assistants                                                             | 683   |
| 43-6013.00 | Medical Secretaries and Administrative Assistants                                                           | 684   |
| 43-6014.00 | Secretaries and Administrative Assistants, Except Legal,   Medical, and Executive                           | 685   |
| 43-9011.00 | Computer operators                                                                                          | 1019  |
| 43-9021.00 | Data Entry Keyers                                                                                           | 686   |
| 43-9022.00 | Word Processors and Typists                                                                                 | 687   |
| 43-9031.00 | Desktop Publishers                                                                                          | 688   |
| 43-9041.00 | Insurance Claims and Policy Processing Clerks                                                               | 689   |
| 43-9051.00 | Mail Clerks and Mail Machine Operators, Except Postal Service                                               | 690   |
| 43-9061.00 | Office Clerks, General                                                                                      | 691   |
| 43-9071.00 | Office Machine Operators, Except Computer                                                                   | 692   |
| 43-9081.00 | Proofreaders and Copy Markers                                                                               | 693   |
| 43-9111.00 | Statistical Assistants                                                                                      | 694   |
| 43-9199.00 | Office and Administrative Support Workers, All Other                                                        | 695   |
| 45-1011.00 | First-Line Supervisors of Farming, Fishing, and Forestry   Workers                                          | 696   |
| 45-2011.00 | Agricultural Inspectors                                                                                     | 697   |
| 45-2021.00 | Animal Breeders                                                                                             | 698   |
| 45-2041.00 | Graders and Sorters, Agricultural Products                                                                  | 699   |
| 45-2091.00 | Agricultural Equipment Operators                                                                            | 700   |
| 45-2092.00 | Farmworkers and Laborers, Crop, Nursery, and Greenhouse                                                     | 701   |
| 45-2093.00 | Farmworkers, Farm, Ranch, and Aquacultural Animals                                                          | 702   |
| 45-2099.00 | Agricultural Workers, All Other                                                                             | 703   |
| 45-3031.00 | Fishing and Hunting Workers                                                                                 | 704   |
| 45-4011.00 | Forest and Conservation Workers                                                                             | 705   |
| 45-4021.00 | Fallers                                                                                                     | 706   |
| 45-4022.00 | Logging Equipment Operators                                                                                 | 707   |
| 45-4023.00 | Log Graders and Scalers                                                                                     | 708   |
| 45-4029.00 | Logging Workers, All Other                                                                                  | 709   |
| 47-1011.00 | First-Line Supervisors of Construction Trades and Extraction   Workers                                      | 710   |
| 47-1011.03 | Solar Energy Installation Managers                                                                          | 711   |
| 47-2011.00 | Boilermakers                                                                                                | 712   |
| 47-2021.00 | Brickmasons and Blockmasons                                                                                 | 713   |
| 47-2022.00 | Stonemasons                                                                                                 | 714   |
| 47-2031.00 | Carpenters                                                                                                  | 715   |
| 47-2041.00 | Carpet Installers                                                                                           | 716   |
| 47-2042.00 | Floor Layers, Except Carpet, Wood, and Hard Tiles                                                           | 717   |
| 47-2043.00 | Floor Sanders and Finishers                                                                                 | 718   |
| 47-2044.00 | Tile and Stone Setters                                                                                      | 719   |
| 47-2051.00 | Cement Masons and Concrete Finishers                                                                        | 720   |
| 47-2053.00 | Terrazzo Workers and Finishers                                                                              | 721   |
| 47-2061.00 | Construction Laborers                                                                                       | 722   |
| 47-2071.00 | Paving, Surfacing, and Tamping Equipment Operators                                                          | 723   |
| 47-2072.00 | Pile Driver Operators                                                                                       | 724   |
| 47-2073.00 | Operating Engineers and Other Construction Equipment Operators                                              | 725   |
| 47-2081.00 | Drywall and Ceiling Tile Installers                                                                         | 726   |
| 47-2082.00 | Tapers                                                                                                      | 727   |
| 47-2111.00 | Electricians                                                                                                | 728   |
| 47-2121.00 | Glaziers                                                                                                    | 729   |
| 47-2131.00 | Insulation Workers, Floor, Ceiling, and Wall                                                                | 730   |
| 47-2132.00 | Insulation Workers, Mechanical                                                                              | 731   |
| 47-2141.00 | Painters, Construction and Maintenance                                                                      | 732   |
| 47-2142.00 | Paperhangers                                                                                                | 733   |
| 47-2151.00 | Pipelayers                                                                                                  | 734   |
| 47-2152.00 | Plumbers, Pipefitters, and Steamfitters                                                                     | 735   |
| 47-2152.04 | Solar Thermal Installers and Technicians                                                                    | 736   |
| 47-2161.00 | Plasterers and Stucco Masons                                                                                | 737   |
| 47-2171.00 | Reinforcing Iron and Rebar Workers                                                                          | 738   |
| 47-2181.00 | Roofers                                                                                                     | 739   |
| 47-2211.00 | Sheet Metal Workers                                                                                         | 740   |
| 47-2221.00 | Structural Iron and Steel Workers                                                                           | 741   |
| 47-2231.00 | Solar Photovoltaic Installers                                                                               | 742   |
| 47-3011.00 | Helpers--Brickmasons, Blockmasons, Stonemasons, and Tile and   Marble Setters                               | 743   |
| 47-3012.00 | Helpers--Carpenters                                                                                         | 744   |
| 47-3013.00 | Helpers--Electricians                                                                                       | 745   |
| 47-3014.00 | Helpers--Painters, Paperhangers, Plasterers, and Stucco Masons                                              | 746   |
| 47-3015.00 | Helpers--Pipelayers, Plumbers, Pipefitters, and Steamfitters                                                | 747   |
| 47-3016.00 | Helpers--Roofers                                                                                            | 748   |
| 47-3019.00 | Helpers, Construction Trades, All Other                                                                     | 749   |
| 47-4011.00 | Construction and Building Inspectors                                                                        | 750   |
| 47-4011.01 | Energy Auditors                                                                                             | 751   |
| 47-4021.00 | Elevator and Escalator Installers and   Repairers                                                           | 752   |
| 47-4031.00 | Fence Erectors                                                                                              | 753   |
| 47-4041.00 | Hazardous Materials Removal Workers                                                                         | 754   |
| 47-4051.00 | Highway Maintenance Workers                                                                                 | 755   |
| 47-4061.00 | Rail-Track Laying and Maintenance Equipment Operators                                                       | 756   |
| 47-4071.00 | Septic Tank Servicers and Sewer Pipe Cleaners                                                               | 757   |
| 47-4091.00 | Segmental Pavers                                                                                            | 758   |
| 47-4099.00 | Construction and Related Workers, All Other                                                                 | 759   |
| 47-4099.03 | Weatherization Installers and Technicians                                                                   | 760   |
| 47-5011.00 | Derrick Operators, Oil and Gas                                                                              | 761   |
| 47-5012.00 | Rotary Drill Operators, Oil and Gas                                                                         | 762   |
| 47-5013.00 | Service Unit Operators, Oil and Gas                                                                         | 763   |
| 47-5022.00 | Excavating and Loading Machine and Dragline Operators, Surface Mining                                       | 764   |
| 47-5023.00 | Earth Drillers, Except Oil and Gas                                                                          | 765   |
| 47-5032.00 | Explosives Workers, Ordnance Handling Experts, and Blasters                                                 | 766   |
| 47-5041.00 | Continuous Mining Machine Operators                                                                         | 767   |
| 47-5043.00 | Roof Bolters, Mining                                                                                        | 768   |
| 47-5044.00 | Loading and Moving Machine Operators, Underground Mining                                                    | 769   |
| 47-5049.00 | Underground Mining Machine Operators, All Other                                                             | 770   |
| 47-5051.00 | Rock Splitters, Quarry                                                                                      | 771   |
| 47-5071.00 | Roustabouts, Oil and Gas                                                                                    | 772   |
| 47-5081.00 | Helpers--Extraction Workers                                                                                 | 773   |
| 47-5099.00 | Extraction Workers, All Other                                                                               | 774   |
| 49-1011.00 | First-Line Supervisors of Mechanics, Installers, and Repairers                                              | 775   |
| 49-2011.00 | Computer, Automated Teller, and Office   Machine Repairers                                                  | 776   |
| 49-2021.00 | Radio, Cellular, and Tower Equipment Installers and Repairers                                               | 777   |
| 49-2022.00 | Telecommunications Equipment Installers and Repairers, Except   Line Installers                             | 778   |
| 49-2091.00 | Avionics Technicians                                                                                        | 779   |
| 49-2092.00 | Electric Motor, Power Tool, and Related Repairers                                                           | 780   |
| 49-2093.00 | Electrical and Electronics Installers and Repairers,   Transportation Equipment                             | 781   |
| 49-2094.00 | Electrical and Electronics Repairers, Commercial and   Industrial Equipment                                 | 782   |
| 49-2095.00 | Electrical and Electronics Repairers, Powerhouse, Substation,   and Relay                                   | 783   |
| 49-2096.00 | Electronic Equipment Installers and Repairers, Motor Vehicles                                               | 784   |
| 49-2097.00 | Audiovisual Equipment Installers and Repairers                                                              | 785   |
| 49-2098.00 | Security and Fire Alarm Systems Installers                                                                  | 786   |
| 49-3011.00 | Aircraft Mechanics and Service   Technicians                                                                | 787   |
| 49-3021.00 | Automotive Body and Related Repairers                                                                       | 788   |
| 49-3022.00 | Automotive Glass Installers and Repairers                                                                   | 789   |
| 49-3023.00 | Automotive Service Technicians and Mechanics                                                                | 790   |
| 49-3031.00 | Bus and Truck Mechanics and Diesel   Engine Specialists                                                     | 791   |
| 49-3041.00 | Farm Equipment Mechanics and Service Technicians                                                            | 792   |
| 49-3042.00 | Mobile Heavy Equipment Mechanics, Except Engines                                                            | 793   |
| 49-3043.00 | Rail Car Repairers                                                                                          | 794   |
| 49-3051.00 | Motorboat Mechanics and Service Technicians                                                                 | 795   |
| 49-3052.00 | Motorcycle Mechanics                                                                                        | 796   |
| 49-3053.00 | Outdoor Power Equipment and Other Small Engine Mechanics                                                    | 797   |
| 49-3091.00 | Bicycle Repairers                                                                                           | 798   |
| 49-3092.00 | Recreational Vehicle Service Technicians                                                                    | 799   |
| 49-3093.00 | Tire Repairers and Changers                                                                                 | 800   |
| 49-9011.00 | Mechanical Door Repairers                                                                                   | 801   |
| 49-9012.00 | Control and Valve Installers and Repairers, Except Mechanical   Door                                        | 802   |
| 49-9021.00 | Heating, Air Conditioning, and   Refrigeration Mechanics and Installers                                     | 803   |
| 49-9031.00 | Home Appliance Repairers                                                                                    | 804   |
| 49-9041.00 | Industrial Machinery Mechanics                                                                              | 805   |
| 49-9043.00 | Maintenance Workers, Machinery                                                                              | 806   |
| 49-9044.00 | Millwrights                                                                                                 | 807   |
| 49-9045.00 | Refractory Materials Repairers, Except Brickmasons                                                          | 808   |
| 49-9051.00 | Electrical Power-Line Installers and Repairers                                                              | 809   |
| 49-9052.00 | Telecommunications Line Installers and Repairers                                                            | 810   |
| 49-9061.00 | Camera and Photographic Equipment Repairers                                                                 | 811   |
| 49-9062.00 | Medical Equipment Repairers                                                                                 | 812   |
| 49-9063.00 | Musical Instrument Repairers and Tuners                                                                     | 813   |
| 49-9064.00 | Watch and Clock Repairers                                                                                   | 814   |
| 49-9069.00 | Precision Instrument and Equipment Repairers, All Other                                                     | 815   |
| 49-9071.00 | Maintenance and Repair Workers,   General                                                                   | 816   |
| 49-9081.00 | Wind Turbine Service Technicians                                                                            | 817   |
| 49-9091.00 | Coin, Vending, and Amusement Machine Servicers and Repairers                                                | 818   |
| 49-9092.00 | Commercial Divers                                                                                           | 819   |
| 49-9094.00 | Locksmiths and Safe Repairers                                                                               | 820   |
| 49-9095.00 | Manufactured Building and Mobile Home Installers                                                            | 821   |
| 49-9096.00 | Riggers                                                                                                     | 822   |
| 49-9097.00 | Signal and Track Switch Repairers                                                                           | 823   |
| 49-9098.00 | Helpers--Installation, Maintenance, and Repair Workers                                                      | 824   |
| 49-9099.00 | Installation, Maintenance, and Repair Workers, All Other                                                    | 825   |
| 49-9099.01 | Geothermal Technicians                                                                                      | 826   |
| 51-1011.00 | First-Line Supervisors of Production and Operating Workers                                                  | 827   |
| 51-2011.00 | Aircraft Structure, Surfaces, Rigging,   and Systems Assemblers                                             | 828   |
| 51-2021.00 | Coil Winders, Tapers, and Finishers                                                                         | 829   |
| 51-2022.00 | Electrical and Electronic Equipment Assemblers                                                              | 830   |
| 51-2023.00 | Electromechanical Equipment Assemblers                                                                      | 831   |
| 51-2031.00 | Engine and Other Machine Assemblers                                                                         | 832   |
| 51-2041.00 | Structural Metal Fabricators and   Fitters                                                                  | 833   |
| 51-2051.00 | Fiberglass Laminators and Fabricators                                                                       | 834   |
| 51-2061.00 | Timing Device Assemblers and Adjusters                                                                      | 835   |
| 51-2092.00 | Team Assemblers                                                                                             | 836   |
| 51-2099.00 | Assemblers and Fabricators, All Other                                                                       | 837   |
| 51-3011.00 | Bakers                                                                                                      | 838   |
| 51-3021.00 | Butchers and Meat Cutters                                                                                   | 839   |
| 51-3022.00 | Meat, Poultry, and Fish Cutters and Trimmers                                                                | 840   |
| 51-3023.00 | Slaughterers and Meat Packers                                                                               | 841   |
| 51-3091.00 | Food and Tobacco Roasting, Baking, and Drying Machine   Operators and Tenders                               | 842   |
| 51-3092.00 | Food Batchmakers                                                                                            | 843   |
| 51-3093.00 | Food Cooking Machine Operators and Tenders                                                                  | 844   |
| 51-3099.00 | Food Processing Workers, All Other                                                                          | 845   |
| 51-4021.00 | Extruding and Drawing Machine Setters, Operators, and Tenders,   Metal and Plastic                          | 846   |
| 51-4022.00 | Forging Machine Setters, Operators, and Tenders, Metal and   Plastic                                        | 847   |
| 51-4023.00 | Rolling Machine Setters, Operators, and Tenders, Metal and   Plastic                                        | 848   |
| 51-4031.00 | Cutting, Punching, and Press Machine Setters, Operators, and   Tenders, Metal and Plastic                   | 849   |
| 51-4032.00 | Drilling and Boring Machine Tool Setters, Operators, and   Tenders, Metal and Plastic                       | 850   |
| 51-4033.00 | Grinding, Lapping, Polishing, and Buffing Machine Tool   Setters, Operators, and Tenders, Metal and Plastic | 851   |
| 51-4034.00 | Lathe and Turning Machine Tool Setters, Operators, and   Tenders, Metal and Plastic                         | 852   |
| 51-4035.00 | Milling and Planing Machine Setters, Operators, and Tenders,   Metal and Plastic                            | 853   |
| 51-4041.00 | Machinists                                                                                                  | 854   |
| 51-4051.00 | Metal-Refining Furnace Operators and Tenders                                                                | 855   |
| 51-4052.00 | Pourers and Casters, Metal                                                                                  | 856   |
| 51-4061.00 | Model Makers, Metal and Plastic                                                                             | 857   |
| 51-4062.00 | Patternmakers, Metal and Plastic                                                                            | 858   |
| 51-4071.00 | Foundry Mold and Coremakers                                                                                 | 859   |
| 51-4072.00 | Molding, Coremaking, and Casting Machine Setters, Operators,   and Tenders, Metal and Plastic               | 860   |
| 51-4081.00 | Multiple Machine Tool Setters, Operators, and Tenders, Metal   and Plastic                                  | 861   |
| 51-4111.00 | Tool and Die Makers                                                                                         | 862   |
| 51-4121.00 | Welders, Cutters, Solderers, and Brazers                                                                    | 863   |
| 51-4122.00 | Welding, Soldering, and Brazing Machine Setters, Operators,   and Tenders                                   | 864   |
| 51-4191.00 | Heat Treating Equipment Setters, Operators, and Tenders, Metal   and Plastic                                | 865   |
| 51-4192.00 | Layout Workers, Metal and Plastic                                                                           | 866   |
| 51-4193.00 | Plating Machine Setters, Operators, and Tenders, Metal and   Plastic                                        | 867   |
| 51-4194.00 | Tool Grinders, Filers, and Sharpeners                                                                       | 868   |
| 51-4199.00 | Metal Workers and Plastic Workers, All Other                                                                | 869   |
| 51-5111.00 | Prepress Technicians and Workers                                                                            | 870   |
| 51-5112.00 | Printing Press Operators                                                                                    | 871   |
| 51-5113.00 | Print Binding and Finishing Workers                                                                         | 872   |
| 51-6011.00 | Laundry and Dry-Cleaning Workers                                                                            | 873   |
| 51-6021.00 | Pressers, Textile, Garment, and   Related Materials                                                         | 874   |
| 51-6031.00 | Sewing Machine Operators                                                                                    | 875   |
| 51-6041.00 | Shoe and Leather Workers and Repairers                                                                      | 876   |
| 51-6042.00 | Shoe Machine Operators and Tenders                                                                          | 877   |
| 51-6051.00 | Sewers, Hand                                                                                                | 878   |
| 51-6052.00 | Tailors, Dressmakers, and Custom Sewers                                                                     | 879   |
| 51-6061.00 | Textile Bleaching and Dyeing Machine Operators and Tenders                                                  | 880   |
| 51-6062.00 | Textile Cutting Machine Setters, Operators, and Tenders                                                     | 881   |
| 51-6063.00 | Textile Knitting and Weaving Machine Setters, Operators, and   Tenders                                      | 882   |
| 51-6064.00 | Textile Winding, Twisting, and Drawing Out Machine Setters,   Operators, and Tenders                        | 883   |
| 51-6091.00 | Extruding and Forming Machine Setters, Operators, and Tenders,   Synthetic and Glass Fibers                 | 884   |
| 51-6092.00 | Fabric and Apparel Patternmakers                                                                            | 885   |
| 51-6093.00 | Upholsterers                                                                                                | 886   |
| 51-6099.00 | Textile, Apparel, and Furnishings Workers, All Other                                                        | 887   |
| 51-7011.00 | Cabinetmakers and Bench Carpenters                                                                          | 888   |
| 51-7021.00 | Furniture Finishers                                                                                         | 889   |
| 51-7031.00 | Model Makers, Wood                                                                                          | 890   |
| 51-7032.00 | Patternmakers, Wood                                                                                         | 891   |
| 51-7041.00 | Sawing Machine Setters, Operators, and Tenders, Wood                                                        | 892   |
| 51-7042.00 | Woodworking Machine Setters, Operators, and Tenders, Except   Sawing                                        | 893   |
| 51-7099.00 | Woodworkers, All Other                                                                                      | 894   |
| 51-8011.00 | Nuclear Power Reactor Operators                                                                             | 895   |
| 51-8012.00 | Power Distributors and Dispatchers                                                                          | 896   |
| 51-8013.00 | Power Plant Operators                                                                                       | 897   |
| 51-8013.03 | Biomass Plant Technicians                                                                                   | 898   |
| 51-8013.04 | Hydroelectric Plant Technicians                                                                             | 899   |
| 51-8021.00 | Stationary Engineers and Boiler   Operators                                                                 | 900   |
| 51-8031.00 | Water and Wastewater Treatment Plant   and System Operators                                                 | 901   |
| 51-8091.00 | Chemical Plant and System Operators                                                                         | 902   |
| 51-8092.00 | Gas Plant Operators                                                                                         | 903   |
| 51-8093.00 | Petroleum Pump System Operators, Refinery Operators, and Gaugers                                            | 904   |
| 51-8099.00 | Plant and System Operators, All Other                                                                       | 905   |
| 51-8099.01 | Biofuels Processing Technicians                                                                             | 906   |
| 51-9011.00 | Chemical Equipment Operators and Tenders                                                                    | 907   |
| 51-9012.00 | Separating, Filtering, Clarifying, Precipitating, and Still   Machine Setters, Operators, and Tenders       | 908   |
| 51-9021.00 | Crushing, Grinding, and Polishing Machine Setters, Operators,   and Tenders                                 | 909   |
| 51-9022.00 | Grinding and Polishing Workers, Hand                                                                        | 910   |
| 51-9023.00 | Mixing and Blending Machine Setters, Operators, and Tenders                                                 | 911   |
| 51-9031.00 | Cutters and Trimmers, Hand                                                                                  | 912   |
| 51-9032.00 | Cutting and Slicing Machine Setters, Operators, and Tenders                                                 | 913   |
| 51-9041.00 | Extruding, Forming, Pressing, and   Compacting Machine Setters, Operators, and Tenders                      | 914   |
| 51-9051.00 | Furnace, Kiln, Oven, Drier, and Kettle   Operators and Tenders                                              | 915   |
| 51-9061.00 | Inspectors, Testers, Sorters,   Samplers, and Weighers                                                      | 916   |
| 51-9071.00 | Jewelers and Precious Stone and Metal Workers                                                               | 917   |
| 51-9071.06 | Gem and Diamond Workers                                                                                     | 918   |
| 51-9081.00 | Dental Laboratory Technicians                                                                               | 919   |
| 51-9082.00 | Medical Appliance Technicians                                                                               | 920   |
| 51-9083.00 | Ophthalmic Laboratory Technicians                                                                           | 921   |
| 51-9111.00 | Packaging and Filling Machine   Operators and Tenders                                                       | 922   |
| 51-9123.00 | Painting, Coating, and Decorating Workers                                                                   | 923   |
| 51-9124.00 | Coating, Painting, and Spraying Machine Setters, Operators,   and Tenders                                   | 924   |
| 51-9141.00 | Semiconductor Processing Technicians                                                                        | 925   |
| 51-9151.00 | Photographic Process Workers and   Processing Machine Operators                                             | 926   |
| 51-9161.00 | Computer Numerically Controlled Tool Operators                                                              | 927   |
| 51-9162.00 | Computer Numerically Controlled Tool Programmers                                                            | 928   |
| 51-9191.00 | Adhesive Bonding Machine Operators and Tenders                                                              | 929   |
| 51-9192.00 | Cleaning, Washing, and Metal Pickling Equipment Operators and   Tenders                                     | 930   |
| 51-9193.00 | Cooling and Freezing Equipment Operators and Tenders                                                        | 931   |
| 51-9194.00 | Etchers and Engravers                                                                                       | 932   |
| 51-9195.00 | Molders, Shapers, and Casters, Except Metal and Plastic                                                     | 933   |
| 51-9195.03 | Stone Cutters and Carvers, Manufacturing                                                                    | 934   |
| 51-9195.04 | Glass Blowers, Molders, Benders, and Finishers                                                              | 935   |
| 51-9195.05 | Potters, Manufacturing                                                                                      | 936   |
| 51-9196.00 | Paper Goods Machine Setters, Operators, and Tenders                                                         | 937   |
| 51-9197.00 | Tire Builders                                                                                               | 938   |
| 51-9198.00 | Helpers--Production Workers                                                                                 | 939   |
| 51-9199.00 | Production Workers, All Other                                                                               | 940   |
| 53-1041.00 | Aircraft Cargo Handling Supervisors                                                                         | 941   |
| 53-1042.00 | First-Line Supervisors of Helpers, Laborers, and Material   Movers, Hand                                    | 942   |
| 53-1042.01 | Recycling Coordinators                                                                                      | 943   |
| 53-1043.00 | First-Line Supervisors of Material-Moving Machine and Vehicle   Operators                                   | 944   |
| 53-1044.00 | First-Line Supervisors of Passenger Attendants                                                              | 945   |
| 53-1049.00 | First-Line Supervisors of Transportation Workers, All Other                                                 | 946   |
| 53-2011.00 | Airline Pilots, Copilots, and Flight Engineers                                                              | 947   |
| 53-2012.00 | Commercial Pilots                                                                                           | 948   |
| 53-2021.00 | Air Traffic Controllers                                                                                     | 949   |
| 53-2022.00 | Airfield Operations Specialists                                                                             | 950   |
| 53-2031.00 | Flight Attendants                                                                                           | 951   |
| 53-3011.00 | Ambulance Drivers and Attendants,   Except Emergency Medical Technicians                                    | 952   |
| 53-3031.00 | Driver/Sales Workers                                                                                        | 953   |
| 53-3032.00 | Heavy and Tractor-Trailer Truck Drivers                                                                     | 954   |
| 53-3033.00 | Light Truck Drivers                                                                                         | 955   |
| 53-3051.00 | Bus Drivers, School                                                                                         | 956   |
| 53-3052.00 | Bus Drivers, Transit and Intercity                                                                          | 957   |
| 53-3053.00 | Shuttle Drivers and Chauffeurs                                                                              | 958   |
| 53-3054.00 | Taxi Drivers                                                                                                | 959   |
| 53-3099.00 | Motor Vehicle Operators, All Other                                                                          | 960   |
| 53-4011.00 | Locomotive Engineers                                                                                        | 961   |
| 53-4013.00 | Rail Yard Engineers, Dinkey Operators, and Hostlers                                                         | 962   |
| 53-4022.00 | Railroad Brake, Signal, and Switch   Operators and Locomotive Firers                                        | 963   |
| 53-4031.00 | Railroad Conductors and Yardmasters                                                                         | 964   |
| 53-4041.00 | Subway and Streetcar Operators                                                                              | 965   |
| 53-4099.00 | Rail Transportation Workers, All Other                                                                      | 966   |
| 53-5011.00 | Sailors and Marine Oilers                                                                                   | 967   |
| 53-5021.00 | Captains, Mates, and Pilots of Water Vessels                                                                | 968   |
| 53-5022.00 | Motorboat Operators                                                                                         | 969   |
| 53-5031.00 | Ship Engineers                                                                                              | 970   |
| 53-6011.00 | Bridge and Lock Tenders                                                                                     | 971   |
| 53-6021.00 | Parking Attendants                                                                                          | 972   |
| 53-6031.00 | Automotive and Watercraft Service Attendants                                                                | 973   |
| 53-6032.00 | Aircraft Service Attendants                                                                                 | 974   |
| 53-6041.00 | Traffic Technicians                                                                                         | 975   |
| 53-6051.00 | Transportation Inspectors                                                                                   | 976   |
| 53-6051.01 | Aviation Inspectors                                                                                         | 977   |
| 53-6051.07 | Transportation Vehicle, Equipment and Systems Inspectors,   Except Aviation                                 | 978   |
| 53-6061.00 | Passenger Attendants                                                                                        | 979   |
| 53-6099.00 | Transportation Workers, All Other                                                                           | 980   |
| 53-7011.00 | Conveyor Operators and Tenders                                                                              | 981   |
| 53-7021.00 | Crane and Tower Operators                                                                                   | 982   |
| 53-7031.00 | Dredge Operators                                                                                            | 983   |
| 53-7041.00 | Hoist and Winch Operators                                                                                   | 984   |
| 53-7051.00 | Industrial Truck and Tractor Operators                                                                      | 985   |
| 53-7061.00 | Cleaners of Vehicles and Equipment                                                                          | 986   |
| 53-7062.00 | Laborers and Freight, Stock, and Material Movers, Hand                                                      | 987   |
| 53-7062.04 | Recycling and Reclamation Workers                                                                           | 988   |
| 53-7063.00 | Machine Feeders and Offbearers                                                                              | 989   |
| 53-7064.00 | Packers and Packagers, Hand                                                                                 | 990   |
| 53-7065.00 | Stockers and Order Fillers                                                                                  | 991   |
| 53-7071.00 | Gas Compressor and Gas Pumping Station Operators                                                            | 992   |
| 53-7072.00 | Pump Operators, Except Wellhead Pumpers                                                                     | 993   |
| 53-7073.00 | Wellhead Pumpers                                                                                            | 994   |
| 53-7081.00 | Refuse and Recyclable Material   Collectors                                                                 | 995   |
| 53-7111.00 | Mine shuttle car operators                                                                                  | 1020  |
| 53-7121.00 | Tank Car, Truck, and Ship Loaders                                                                           | 996   |
| 53-7199.00 | Material Moving Workers, All Other                                                                          | 997   |
| 55-1011.00 | Air Crew Officers                                                                                           | 998   |
| 55-1012.00 | Aircraft Launch and Recovery Officers                                                                       | 999   |
| 55-1013.00 | Armored Assault Vehicle Officers                                                                            | 1000  |
| 55-1014.00 | Artillery and Missile Officers                                                                              | 1001  |
| 55-1015.00 | Command and Control Center Officers                                                                         | 1002  |
| 55-1016.00 | Infantry Officers                                                                                           | 1003  |
| 55-1017.00 | Special Forces Officers                                                                                     | 1004  |
| 55-1019.00 | Military Officer Special and Tactical Operations Leaders, All   Other                                       | 1005  |
| 55-2011.00 | First-Line Supervisors of Air Crew Members                                                                  | 1006  |
| 55-2012.00 | First-Line Supervisors of Weapons Specialists/Crew Members                                                  | 1007  |
| 55-2013.00 | First-Line Supervisors of All Other Tactical Operations Specialists                                         | 1008  |
| 55-3011.00 | Air Crew Members                                                                                            | 1009  |
| 55-3012.00 | Aircraft Launch and Recovery Specialists                                                                    | 1010  |
| 55-3013.00 | Armored Assault Vehicle Crew Members                                                                        | 1011  |
| 55-3014.00 | Artillery and Missile Crew Members                                                                          | 1012  |
| 55-3015.00 | Command and Control Center Specialists                                                                      | 1013  |
| 55-3016.00 | Infantry                                                                                                    | 1014  |
| 55-3018.00 | Special Forces                                                                                              | 1015  |
| 55-3019.00 | Military Enlisted Tactical Operations and Air/Weapons Specialists and   Crew Members, All Other             | 1016  |
| 99999      | Not in universe                                                                                             | 99999 |
