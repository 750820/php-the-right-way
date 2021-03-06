---
isChild: true
---

## Behavior Driven Development {#behavior_driven_development_title}

Istnieją dwa rodzaje BDD (Behavior-Driven Development): SpecBDD i StoryBDD. Pierwszy z nich charakteryzuje się
technicznym podejściem, gdzie istotny jest kod i jego zachowanie, podczas gdy drugi reprezentuje podejście biznesowe,
gdzie najważniejszą kwestią jest to jak produkt będzie funkcjonował z perspektywy klienta. W PHP dostępne są frameworki
wspierające oba te typy.

W StoryBDD piszesz zrozumiałe dla człowieka historyjki, które opisują zachowanie Twojej aplikacji. Są one później
uruchamiane jako testy aplikacji. Frameworkiem, który wspiera taki typ testowania jest [Behat](http://behat.org/),
inspirowany projektem [Cucumber](http://cukes.info/) dla Ruby'ego. Do opisywania historyjek w Behat używa się języka
Gherkin DSL (Gherkin Domain Specific Language).

W SpecBDD piszesz natomiast specyfikacje opisujące w jaki sposób powinien zachowywać się Twój kod. Zamiast testować
funkcję, czy metodę, opisujesz jak powinna się zachowywać. Ten typ BDD wspierany jest przez framework PHPSpec, który
z kolei inspirowany jest projektem [RSpec project](http://rspec.info/), także dla Ruby'ego.

### Linki    

* [Behat](http://behat.org/) 
* [PHPSpec](http://www.phpspec.net/)
* [Codeception](http://www.codeception.com) framework do testowania aplikacji korzystający z zasad BDD
