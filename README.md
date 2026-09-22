








Алхам 3

| Сценарио | SLI | Босго | Цонх/Нөхцөл|
| --- | --- | --- | --- |
|Performance| /cart/add latency p(95) | <57mc | 20VU, 1min |
|Reliability| /pay error rate | <8% | 1min ,20VU |
|Availability| check success rate | >90% | 1min, 20VU |
|Performance| /report latency p(95) | <450mc | 20VU ,1min| 

p(95) = 200ms ээр ажилуулж бодит p(95) = 37.87мс гаргаж авсан ба энийгээ лаборторын ажил 2 той ижил аргаар зайг 1.5 дахин үржүүлж томруулсан. 

Алхам 5

Chaos туршилтын үр дүн 
|Үзүүлэлт|  гаралт|
| --- | --- | 
|checks (availability) | 87.27% -Fail |
|pay error | 15.45%  - Fail |
|cart | 6.55ms - Pass |
|cart  амжилтгүй   | 209/1883 |
|report амжилтгүй | 219/1883 |
|pay амжилтгүй | 291/ 1833 |


Алхам 6

 /report - ын threshold -ыг гараас p(95)< 100 мс болгож эвдэхэд  k6 exit code = [99] гэж буцаасан ба энэ нь CI pipleline - д build -ийг зогсоох дохио болно. 
 
 




