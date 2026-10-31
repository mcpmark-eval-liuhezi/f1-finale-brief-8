# 2021 Abu Dhabi Grand Prix — Research Brief & Retrospective Trail

arat founding session of the 2021 season-closing Abu Dhabi Grand Prix (Yas Marina), the race where Max Verstappen and Lewis Hamilton arrived level on points and the World Championship was decided on the final lap.

## Race Session

- **Session:** Race (Grand Prix race session)
- **Race:** Abu Dhabi Grand Prix — round 22 of the 2021 Formula 1 season
- **Circuit:** Yas Marina Circuit, Abu Dhabi, UAE
- **Date (as reported by the data source):** 2021-12-12
- **Start time (as reported by the data source):** 13:00:00Z
- **Session key:** Not reported by the data source — the historical-sessions lookup returned an empty result set for every filter combination attempted (year 2021; session name "Race"; country "United Arab Emirates"/"UAE"; location "Abu Dhabi"/"Yas Marina"; circuit short name "yas_marina"/"Yas Marina"). The session key could not be resolved from the source, so it is recorded here as unavailable rather than guessed.

## Classified Race Results — Round 22, 2021 (Abu Dhabi GP)

| Pos | Driver | Permanent No. | Code | Nationality | DOB | Points | Grid | Laps | Status | Time |
|-----|--------|---------------|------|-------------|-----|--------|------|------|--------|------|
| 1 | Max Verstappen (Red Bull) | 33 | VER | Dutch | 1997-09-30 | 26 | 1 | 58 | Finished | 1:30:17.345 |
| 2 | Lewis Hamilton (Mercedes) | 44 | HAM | British | 1985-01-07 | 18 | 2 | 58 | Finished | +2.256 |
| 3 | Carlos Sainz (Ferrari) | 55 | SAI | Spanish | 1994-09-01 | 15 | 5 | 58 | Finished | +5.173 |
| 4 | Yuki Tsunoda (AlphaTauri) | 22 | TSU | Japanese | 2000-05-11 | 12 | 8 | 58 | Finished | +5.692 |
| 5 | Pierre Gasly (AlphaTauri) | 10 | GAS | French | 1996-02-07 | 10 | 12 | 58 | Finished | +6.531 |
| 6 | Valtteri Bottas (Mercedes) | 77 | BOT | Finnish | 1989-08-28 | 8 | 6 | 58 | Finished | +7.463 |
| 7 | Lando Norris (McLaren) | 1 | NOR | British | 1999-11-13 | 6 | 3 | 58 | Finished | +59.200 |
| 8 | Fernando Alonso (Alpine) | 14 | ALO | Spanish | 1981-07-29 | 4 | 11 | 58 | Finished | +1:01.708 |
| 9 | Esteban Ocon (Alpine) | 31 | OCO | French | 1996-09-17 | 2 | 9 | 58 | Finished | +1:04.026 |
| 10 | Charles Leclerc (Ferrari) | 16 | LEC | Monegasque | 1997-10-16 | 1 | 7 | 58 | Finished | +1:06.057 |
| 11 | Sebastian Vettel (Aston Martin) | 5 | VET | German | 1987-07-03 | 0 | 15 | 58 | Finished | +1:07.527 |

Notes on the classified results:
- Verstappen started from pole (grid 1), led the race, and took the win in 1:30:17.345 with the fastest lap of the race (1:26.103 on lap 39, rank 1).
- Hamilton finished 2nd, +2.256s, having started 2nd; he took 18 of 26 available points (race win + fastest lap).
- Sainz finished 3rd for Ferrari, +5.173s, starting 5th.
- Norris is listed with a temporary "1" as his permanent number in the results feed (car number 1); his career permanent number is 4.

## Driver Profiles (as returned by the profile lookup)

### Lewis Hamilton
- **Permanent number:** 44
- **Three-letter code:** HAM
- **Nationality:** British
- **Date of birth:** 1985-01-07
- **Profile link:** http://en.wikipedia.org/wiki/Lewis_Hamilton

### Max Verstappen
- **Permanent number:** 3
- **Three-letter code:** VER
- **Nationality:** Dutch
- **Date of birth:** 1997-09-30
- **Profile link:** http://en.wikipedia.org/wiki/Max_Verstappen

### Carlos Sainz
- **Permanent number:** 55
- **Three-letter code:** SAI
- **Nationality:** Spanish
- **Date of birth:** 1994-09-01
- **Profile link:** http://en.wikipedia.org/wiki/Carlos_Sainz_Jr.

## Podium in Finishing Order

1. **Max Verstappen** (Red Bull) — car no. 33, 26 points
2. **Lewis Hamilton** (Mercedes) — car no. 44, 18 points
3. **Carlos Sainz** (Ferrari) — car no. 55, 15 points

## Context for the Newsletter

Hamilton had won the prior five races and led the championship by 12 points going into Yas Marina. Verstappen's Red Bull started from pole; Hamilton started 2nd and claimed the fastest lap. In the closing laps,安全 employs a late restart strategy; Verstappen held off Hamilton on the final lap to seal the win and the 2021 World Drivers' Championship — matching the profile of a round decided on the last lap with the title level entering the session.

## Data Sources & Retrieval Trail

1. 2021 season calendar & round 22 details (race name, circuit, date 2021-12-12, start time 13:00:00Z) — race results feed.
2. Classified race results for round 22, 2021 — driver positions, points, grid, laps, status, times, fastest lap.
3. Driver profile lookups for hamilton, verstappen, sainz — permanent number, code, nationality, date of birth, profile URL.
4. Historical-sessions lookup for the race session at Yas Marina 2021 — returned empty for all filter combinations; session key unavailable from source.

## Files in This Repository

- `research/abu-dhabi-2021-finale/SUMMARY.md` — this research summary (brership of the round).
- Pull request opens this summary file for editor review before merge into `main`.
