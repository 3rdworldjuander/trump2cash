## Benchmark Report

This breakdown of the analysis results and market performance validates the current implementation against historical data.

Use this command to regenerate the benchmark report after changes to the algorithm or data:
```shell
$ ./benchmark.py > benchmark.md
```

### Events overview

Here's each tweet with the results of its analysis and individual market performance.

##### [12/6/2016 8:52 AM (Tuesday)](https://twitter.com/realDonaldTrump/status/806134244384899072)

> Boeing is building a brand new 747 Air Force One for future presidents, but costs are out of control, more than $4 billion. Cancel order!

*Strategy*

Company | Root | Sentiment | Strategy | Reason
--------|------|-----------|----------|-------
Boeing | - | -0.1 :thumbsdown: | bear | negative sentiment

*Performance*

Ticker | Exchange | Price @ tweet | Price @ close | Gain
-------|----------|---------------|---------------|-----
BA | New York Stock Exchange | $152.16 | $152.30 | -0.092%

##### [12/11/2016 10:29 AM (Sunday)](https://twitter.com/realDonaldTrump/status/807970490635743237)

> Whether I choose him or not for "State"- Rex Tillerson, the Chairman &amp; CEO of ExxonMobil, is a world class player and dealmaker. Stay tuned!

*Strategy*

Company | Root | Sentiment | Strategy | Reason
--------|------|-----------|----------|-------
ExxonMobil | - | 0.2 :thumbsup: | hold | market closed
ExxonMobil | PNC Financial Services | 0.2 :thumbsup: | hold | market closed
ExxonMobil | BlackRock | 0.2 :thumbsup: | hold | market closed
ExxonMobil | State Street Corporation | 0.2 :thumbsup: | hold | market closed

*Performance*

Ticker | Exchange | Price @ tweet | Price @ close | Gain
-------|----------|---------------|---------------|-----
XOM | New York Stock Exchange | - | - | 0.000%
PNC | New York Stock Exchange | - | - | 0.000%
BLK | New York Stock Exchange | - | - | 0.000%
STT | New York Stock Exchange | - | - | 0.000%

##### [12/12/2016 8:26 AM (Monday)](https://twitter.com/realDonaldTrump/status/808301935728230404)

> The F-35 program and cost is out of control. Billions of dollars can and will be saved on military (and other) purchases after January 20th.

*Strategy*

Company | Root | Sentiment | Strategy | Reason
--------|------|-----------|----------|-------
Lockheed Martin Aeronautics | Lockheed Martin | 0 :neutral_face: | hold | neutral sentiment

*Performance*

Ticker | Exchange | Price @ tweet | Price @ close | Gain
-------|----------|---------------|---------------|-----
LMT | New York Stock Exchange | $260.47 | $253.25 | 0.000%

##### [12/13/2016 6:43 AM (Tuesday)](https://twitter.com/realDonaldTrump/status/808638507161882624)

> I have chosen one of the truly great business leaders of the world, Rex Tillerson, Chairman and CEO of ExxonMobil, to be Secretary of State.

*Strategy*

Company | Root | Sentiment | Strategy | Reason
--------|------|-----------|----------|-------
ExxonMobil | - | 0.5 :thumbsup: | hold | market closed
ExxonMobil | PNC Financial Services | 0.5 :thumbsup: | hold | market closed
ExxonMobil | BlackRock | 0.5 :thumbsup: | hold | market closed
ExxonMobil | State Street Corporation | 0.5 :thumbsup: | hold | market closed

*Performance*

Ticker | Exchange | Price @ tweet | Price @ close | Gain
-------|----------|---------------|---------------|-----
XOM | New York Stock Exchange | $90.98 | $92.27 | 0.000%
PNC | New York Stock Exchange | $114.07 | $114.70 | 0.000%
BLK | New York Stock Exchange | $390.28 | $392.64 | 0.000%
STT | New York Stock Exchange | $80.39 | $79.10 | 0.000%

##### [12/17/2016 4:17 PM (Saturday)](https://twitter.com/realDonaldTrump/status/810232514749075456)

