- title : Event Driven Architecture
- description : Event Driven Architecture & Kafka
- author : Nick Blair
- theme : Simple
- transition : none

***

## Event Driven Architecture

***

## Quiz

---

![](images/quiz/eb.png)

---

![](images/quiz/eb_a.png)

---

![](images/quiz/rs.png)

---

![](images/quiz/rs_a.png)

---

![](images/quiz/sf1.png)

---

![](images/quiz/sf2.png)

---

![](images/quiz/sf_a.png)

---

![](images/quiz/p.png)

---

![](images/quiz/p_a.png)

---

![](images/quiz/e.png)

---

![](images/quiz/e_a.png)

---

![](images/quiz/js.png)

---

![](images/quiz/js_a.png)

---

![](images/quiz/csfs.png)

---

![](images/quiz/csfs_a.png)

---

![](images/quiz/g.png)

---

![](images/quiz/g_a.png)

---

![](images/quiz/gh.png)

---

![](images/quiz/gh_a.png)

---

![](images/quiz/k.png)

---

![](images/quiz/k_a.png)

***

## Service Oriented Architecture

---

#### Service Oriented Architecture

![](images/soa/manageable.png)

---

#### Service Oriented Architecture

![](images/soa/manageable2.png)

' point to point
' growth scale / surfaces / complexity

---

#### Service Oriented Architecture

![](images/soa/unmanageable.png)

' pull problem - of lines of connectivity increases
' push problem - multiple touch points
' any one system is easy to manage but hard to debug the full thing
' dependencies between teams

---

## Event Driven Architecture

---

#### Event Driven Architecture

![](images/eda/broker.png)

---

#### Event Driven Architecture

![](images/eda/brokericon.png)

---
#### Event Driven Architeture

![](images/eda/pull.png)

' inverts the push relationship between services
' pull model is improved because new systems can subscribe
' capture and store their own data for private use

---

![](images/eda/tree.png)

' problem that if noone is subscribed then that data is lost
' problem for new services that can only subscribe from that moment in time

---

![](images/eda/nosubscribers.png)

---

![](images/eda/venn1.png)

---

![](images/eda/venn2.png)

---

![](images/eda/venn3.png)

---

![](images/eda/commitlog.png)

' new service can replay all messages since beginning of time and catch up
' existing service can replay messages it misprocessed or rehydrate its db

---

#### Intelligent Alerts

![](images/eda/alerts.png)

---

#### Intelligent Alerts

![](images/eda/alerts_plus.png)

---

![](images/eda/arch.png)

---

### Event Driven Architecture

- Single source of truth

---

### Event Driven Architecture

- Single source of truth
- Permits more surfaces

---

### Event Driven Architecture

- Single source of truth
- Permits more surfaces
- Reduces team dependencies

---

### FIN