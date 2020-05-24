# covid19 Russia Moscow stats

This repo contains notebook, which was being made during the pandemic of COVID-19. Notebook had been started **at the beginning of April 2020**, before any good visualizations of Moscow COVID statistics were made, so the main aim was to look at the data and watch the spread of epidemic in Moscow, considering **restrictions imposed by government**:

- Since 30th of March: "Self-isolation (Holidays) mode" (Russia, including Moscow);
- Since 15th of April: Permits for moving around the Moscow (public and personal transport);
- Since 12th of May: Mandatory wearing of masks and gloves (in public places and transport);

There are visualizations:

1. Number of tests in Russia and regions;
2. New cases daily in Russia and regions;
3. Detection rate in Russia

## Data sources:

- [official site](https://стопкоронавирус.рф/)
- [yandex stats](https://yandex.ru/covid19/stat?utm_source=main_graph&geoId=213)
- [lentach telegram channel](https://t.me/lentachold)
- [wiki about epedemic in Russia](https://ru.wikipedia.org/wiki/%D0%A0%D0%B0%D1%81%D0%BF%D1%80%D0%BE%D1%81%D1%82%D1%80%D0%B0%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5_COVID-19_%D0%B2_%D0%A0%D0%BE%D1%81%D1%81%D0%B8%D0%B8)
- [John Hopkins University data](https://coronavirus.jhu.edu/map.html)


## Comments:

- There are data about new infected cases and tests made:
    - sinse 6th of March 2020;
- Due to the noise of data in first month of epidemic (March 2020) meaningfull statistics about tests were made sinse 15th-30th of March 2020;
- new cases data was collected about:
    - Moscow;
    - Moscow Region (MR);
    - Saint Petersburg (SPB);
    - Leningrad region (LR);
    - Russia;
- Number of tests made by russian regions is not available, there was only aggregated russian number of tests, so **number of tests in regions is an estimate**;
- Num of tests in region = russia_new_tests * region_new_cases / russia_new_cases;
- Detection rate in russia = "new cases daily"/ "new tests daily"
- Several days were missing, so interpolation was made.

## 1. Number of tests

![Russia num tests cumulative](https://github.com/mike-chesnokov/covid19_russia_moscow/blob/master/pictures/russia_num_tests_cumulative.png)

![Regions num tests daily](https://github.com/mike-chesnokov/covid19_russia_moscow/blob/master/pictures/num_tests_by_region.png)

## 2. New cases

![Russia new cases cumulative](https://github.com/mike-chesnokov/covid19_russia_moscow/blob/master/pictures/russia_num_new_cases_daily_cumulative.png)

![Regions new cases daily](https://github.com/mike-chesnokov/covid19_russia_moscow/blob/master/pictures/num_new_cases_by_region.png)

## 3. Detection rate

![Russia detection rate](https://github.com/mike-chesnokov/covid19_russia_moscow/blob/master/pictures/russia_detection_rate_daily.png)
