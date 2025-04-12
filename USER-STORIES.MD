### User Story 1: Jako użytkownik, chcę mieć zapisaną docelową temperaturę

**Jako** użytkownik  
**Chcę** aby system posiadał zapisaną temperaturę docelową, dla której ma się włączać lub wyłączać klimatyzacja  
**Aby** nie musieć ustawiać jej za każdym razem

**Kryteria akceptacji:**

- Domyślna temperatura jest zapisana w systemie (np. 22°C)
- Użytkownik może ją zmienić tylko w ustawieniach systemu
- Po zmianie temperatura jest zapamiętywana na stałe (do kolejnej zmiany)

---

### User Story 2: Jako system, chcę odbierać dane z czujnika temperatury

**Jako** system  
**Chcę** cyklicznie odbierać aktualną temperaturę z czujnika  
**Aby** móc porównać ją z zapisaną wartością docelową

**Kryteria akceptacji:**

- System odbiera dane co 1 minutę
- Dane zawierają aktualną temperaturę w °C

---

### User Story 3: Jako system, chcę automatycznie włączyć klimatyzację

**Jako** system  
**Chcę** automatycznie włączyć klimatyzację, gdy temperatura przekroczy zapisaną wartość docelową  
**Aby** schłodzić pomieszczenie do odpowiedniego poziomu

**Kryteria akceptacji:**

- Klimatyzacja włącza się, gdy temperatura > docelowa + 0.5°C (margines)
- Status klimatyzacji zmienia się na "Włączona"

---

### User Story 4: Jako system, chcę automatycznie wyłączyć klimatyzację

**Jako** system  
**Chcę** automatycznie wyłączyć klimatyzację, gdy temperatura osiągnie zapisaną wartość docelową  
**Aby** utrzymać temperaturę i oszczędzać energię

**Kryteria akceptacji:**

- Klimatyzacja wyłącza się, gdy temperatura ≤ docelowa
- Status klimatyzacji zmienia się na "Wyłączona"

---

### User Story 5: Jako użytkownik, chcę widzieć aktualną temperaturę i status klimatyzacji

**Jako** użytkownik  
**Chcę** widzieć bieżącą temperaturę oraz informację, czy klimatyzacja jest włączona  
**Aby** mieć kontrolę i wiedzę o działaniu systemu

**Kryteria akceptacji:**

- Aktualna temperatura oraz status klimatyzacji są widoczne w panelu
