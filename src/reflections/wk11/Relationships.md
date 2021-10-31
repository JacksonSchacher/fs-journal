# Relationships

## Primary Key / Foreign Key
---
primary keys are unique identities for properties on a table. 
foreign keys are used to reference data on another table

---

## Alias
---
declared variable for a table that helps condense code and keeps from repeating code. 

---

## Join
---
SELECT
d.*,
p.*
FROM doctors d
JOIN patients p ON p.id = d.patientId
WHERE d.id = @id

---

GITHUB: https://github.com/JacksonSchacher/AllSpice