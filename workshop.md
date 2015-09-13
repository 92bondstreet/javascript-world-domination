# DRIVY

---

## peer-to-peer car rental service

Any person, call the `driver` can book a car
for given dates/distance.


---

# Peugeot 306
# Range Rover Sport
# Porsche Boxter

---

# 6 exercise with JavaScript

https://github.com/92bondstreet/web-application-architectures/tree/master/WS1

---

## DRY - Don't repeat yourself
## DOT - Do One Thing
## KISS - Keep It Simple Stupid
## LIM - Less Is More

---

# Euro-Kilometers
## EX 1

---

## rental price

> rental price = time + distance

---

# Drive more, pay less
## EX 2

---

## Decreasing pricing

* 10% after 1 day
* 30% after 4 days
* 50% after 10 days

---

# Give me all your money
## EX 3

---

## Commission

> 30% of the rental price

* insurance → half of commission
* roadside assistance → 1€ per day
* drivy → the rest

---

# The famous deductible
## EX 4

---

## The deductible

> 4€/day

The driver is charged an additional 4€/day when he chooses the "deductible reduction" option.

---

# Pay the actors
## EX 5

---

## The actors

- **the driver** must pay the **rental price** and the **(optional) deductible reduction**
- **the owner** receives the **rental price** minus the **commission**

---

- **the insurance** receives its part of the **commission**
- **the assistance** receives its part of the **commission**
- **drivy receives** its part of the **commission**, plus the **deductible reduction**

---

# Rental modification
## EX 6

---

## New dates and distance

> Some users want to modify the dates/distance for a given rental.
