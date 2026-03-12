PROGETTO 1
Trading Order API – BDD Test Automation Framework

Questo sarebbe perfetto.

Idea

Simuli un sistema di trading semplice con API o logica mockata:

create order

cancel order

reject order if insufficient funds

validate order status

basic risk checks

Obiettivo

Costruire un framework QA automation con:

Java

Cucumber

JUnit

eventualmente Rest Assured

report finale

feature files chiari

Scenari possibili

ordine buy accettato se il saldo è sufficiente

ordine buy rifiutato se il saldo non basta

ordine sell accettato se il cliente possiede abbastanza quantity

ordine cancellato correttamente

ordine con simbolo non valido rifiutato

ordine duplicato gestito correttamente

Cosa dimostra

BDD

Cucumber

Java automation

domain thinking simile a financial markets

structured test framework

Nome GitHub forte

trading-order-bdd-automation

Struttura ideale repo

src/test/resources/features

src/test/java/stepdefinitions

src/test/java/runners

src/main/java/utils

README.md

test-report

bug-examples.md

Valore enorme a colloquio

Potrai dire:

I built a BDD-based automation framework in Java for a simplified trading order workflow, covering positive and negative scenarios such as insufficient funds, invalid symbols and order cancellation.
