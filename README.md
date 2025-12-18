# DOCUMENTAȚIE PROIECT: UniResurse (Bibliotecă Digitală)

## EXERCIȚIUL 1: Viziunea Produsului

### 1.1. Oportunitatea și Problema
**Problema:** Studenții pierd timp căutând materiale didactice dispersate pe grupuri de social media sau drive-uri neorganizate.
**Soluția:** O platformă centralizată unde materialele sunt organizate pe ani, materii și tipuri de resurse, gestionată de comunitatea studențească.

### 1.2. Părțile Implicate
* **Utilizatori:** Studenții (care încarcă și descarcă materiale), Profesorii (care pot valida materialele).
* **Stakeholders:** Asociațiile studențești (administrare), Universitatea (furnizor infrastructură).

### 1.3. Capabilitățile Produsului
* Încărcarea documentelor în formate uzuale (PDF, DOCX, ZIP).
* Căutare avansată după materie, profesor și an de studiu.
* Sistem de rating/votare pentru calitatea materialelor.

---

## EXERCIȚIUL 2: Specificații Software (SRS)

### 2.1. Specificații Funcționale
* **SF1:** Sistemul trebuie să permită autentificarea exclusivă folosind adresa de email instituțională (@student.utcluj.ro).
* **SF2:** La încărcarea unui material, utilizatorul este obligat să selecteze materia și anul de studiu dintr-o listă predefinită.

### 2.2. Specificații de Sistem
* **SS1:** Platforma trebuie să suporte încărcarea fișierelor de până la 50 MB per upload.
* **SS2:** Timpul de răspuns la căutarea unui document trebuie să fie sub 2 secunde.

### 2.3. Specificații de Interfață
* **SI1:** Lista de rezultate trebuie să afișeze pentru fiecare document: titlul, autorul, tipul fișierului și rating-ul (1-5 stele).
