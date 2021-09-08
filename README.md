# Order-Sales-Analysis-with-Athena

SELECT * FROM OrderSales WHERE Units BETWEEN 1228 AND 1404

accession_number_int|accession_number    |cik  |company_name|filing_date|document_type|document_period_end_date|current_fiscal_year_end_date|document_fiscal_year_focus|document_fiscal_period_focus|current_fiscal_year_end_month|amendment_flag|assigned_sic|irs_number|state_of_incorporation|mailing_address_street1   |mailing_address_street2|mailing_address_city|mailing_address_state|mailing_address_zip|business_address_street1  |business_address_street2|business_address_city|business_address_state|business_address_zip|mailing_phone_number|business_phone_number|
--------------------|--------------------|-----|------------|-----------|-------------|------------------------|----------------------------|--------------------------|----------------------------|-----------------------------|--------------|------------|----------|----------------------|--------------------------|-----------------------|--------------------|---------------------|-------------------|--------------------------|------------------------|---------------------|----------------------|--------------------|--------------------|---------------------|
       9341019000008|0000093410-19-000008|93410|CHEVRON CORP| 2019-02-22|10-K         |              2018-12-31|--12-31                     |                      2018|FY                          |                           12|false         |        2911|940890210 |DE                    |6001 BOLLINGER CANYON ROAD|                       |SAN RAMON           |CA                   |94583              |6001 BOLLINGER CANYON ROAD|                        |SAN RAMON            |CA                    |94583               |                    |925-842-1000         |
       9341018000010|0000093410-18-000010|93410|CHEVRON CORP| 2018-02-22|10-K         |              2017-12-31|--12-31                     |                      2017|FY                          |                           12|false         |        2911|940890210 |DE                    |6001 BOLLINGER CANYON ROAD|                       |SAN RAMON           |CA                   |94583              |6001 BOLLINGER CANYON ROAD|                        |SAN RAMON            |CA                    |94583               |                    |925-842-1000         |
       9341017000013|0000093410-17-000013|93410|CHEVRON CORP| 2017-02-23|10-K         |              2016-12-31|--12-31                     |                      2016|FY                          |                           12|false         |        2911|940890210 |DE                    |6001 BOLLINGER CANYON ROAD|                       |SAN RAMON           |CA                   |94583              |6001 BOLLINGER CANYON ROAD|                        |SAN RAMON            |CA                    |94583               |                    |925-842-2815         |
       9341016000049|0000093410-16-000049|93410|CHEVRON CORP| 2016-02-25|10-K         |              2015-12-31|--12-31                     |                      2015|FY                          |                           12|false         |        2911|940890210 |DE                    |6001 BOLLINGER CANYON ROAD|                       |SAN RAMON           |CA                   |94583              |6001 BOLLINGER CANYON ROAD|                        |SAN RAMON            |CA                    |94583               |                    |925-842-1000         |
       9341015000010|0000093410-15-000010|93410|CHEVRON CORP| 2015-02-20|10-K         |              2014-12-31|--12-31                     |                      2014|FY                          |                           12|false         |        2911|940890210 |DE                    |6001 BOLLINGER CANYON ROAD|                       |SAN RAMON           |CA                   |94583              |6001 BOLLINGER CANYON ROAD|                        |SAN RAMON            |CA                    |94583               |                    |925-842-1000         |
       9341014000011|0000093410-14-000011|93410|CHEVRON CORP| 2014-02-21|10-K         |              2013-12-31|--12-31                     |                      2013|FY                          |                           12|false         |        2911|940890210 |DE                    |6001 BOLLINGER CANYON ROAD|                       |SAN RAMON           |CA                   |94583              |6001 BOLLINGER CANYON ROAD|                        |SAN RAMON            |CA                    |94583               |                    |925-842-1000         |
       9341013000003|0000093410-13-000003|93410|CHEVRON CORP| 2013-02-22|10-K         |              2012-12-31|--12-31                     |                      2012|FY                          |                           12|false         |        2911|940890210 |DE                    |6001 BOLLINGER CANYON ROAD|                       |SAN RAMON           |CA                   |94583              |6001 BOLLINGER CANYON ROAD|                        |SAN RAMON            |CA                    |94583               |                    |925-842-1000         |
      95012312002976|0000950123-12-002976|93410|CHEVRON CORP| 2012-02-23|10-K         |              2011-12-31|--12-31                     |                      2011|FY                          |                           12|false         |        2911|940890210 |DE                    |6001 BOLLINGER CANYON ROAD|                       |SAN RAMON           |CA                   |94583              |6001 BOLLINGER CANYON ROAD|                        |SAN RAMON            |CA                    |94583               |                    |925-842-1000         |
      95012311017688|0000950123-11-017688|93410|CHEVRON CORP| 2011-02-24|10-K         |              2010-12-31|--12-31                     |                      2010|FY                          |                           12|false         |        2911|940890210 |DE                    |6001 BOLLINGER CANYON ROAD|                       |SAN RAMON           |CA                   |94583              |6001 BOLLINGER CANYON ROAD|                        |SAN RAMON            |CA                    |94583               |                    |925-842-1000         |
      95012310016846|0000950123-10-016846|93410|CHEVRON CORP| 2010-02-25|10-K         |              2009-12-31|--12-31                     |                          |                            |                           12|false         |        2911|940890210 |DE                    |6001 BOLLINGER CANYON ROAD|                       |SAN RAMON           |CA                   |94583              |6001 BOLLINGER CANYON ROAD|                        |SAN RAMON            |CA                    |94583               |                    |925-842-1000         |

