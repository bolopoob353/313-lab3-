Алхам 3

| Сценарио | SLI | Босго | Цонх/Нөхцөл|
| --- | --- | --- | --- |
|Performance| /cart/add latency p(95) | <57mc | 20VU, 1min |
|Reliability| /pay error rate | <8% | 1min ,20VU |
|Availability| check error | >90% | 1min, 20VU |
|Performance| /report latency p(95) | <450mc | 20VU ,1min| 

p(95) = 200ms ээр ажилуулж бодит 95 = 37.87мс гаргаж авсан ба энийгээ лаборторын ажил 2 той ижил аргаар зайг 1.5 дахин үржүүлж томруулсан. 

Алхам 5

Chaos туршилтын үр дүн 
Тест ажиллаж байх 20 секундын үед серверийг зогсоож 10 секунд хүлээгээд дахин асаасан 
checks threshold (rate >90): 87.27% FAIL
cart report endpoint -ийн 209, 219 хүсэлт амжилтгүй болсон 
pay error rate 15.45% болж threshold (8% )-аас давсан  Fail



