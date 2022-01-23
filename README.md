# ABTest-CookieCatsGameDataSet-

Source: https://www.kaggle.com/mursideyarkin/mobile-games-ab-testing-cookie-cats

Task: make AB test for this dataset.
Result: no difference between A and B groups.

There are two versions of game 'gate_30'(group A) and 'gate_40'(group B)

Metrics - retention_1(player came back after 1 day after installing)
and retention_7(player came back after 7 days after installing)

I used chi-2 test, worked in Jupyter Notebook.

A\B test showed no difference between A and B groups.
A\A test showed statisticaly significant difference for A\A groups for 7 days period.
It means that there are more subgroups in A group and we must consider it.
