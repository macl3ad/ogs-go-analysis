# OGS Go Performance Analysis

## Overview
This is an analysis of my personal match history on the Online Go Server ([OGS](https://online-go.com/)). Go is a territory-based strategy game ([Wikipedia](https://en.wikipedia.org/wiki/Go_(game)). While the classic board is 19x19, this study focuses on 9x9, a high-speed tactical format

## Dataset
* **Source:** 150 games pulled via OGS API
* **Context:** Mostly weekend sessions, reflecting my performance during leisure time
* **Details:** Match outcomes, point margins, stone colors, and opponent ratings

## Built with
* **Python** (Pandas, Seaborn, Matplotlib)

### Files
* [go_analysis.ipynb](go_analysis.ipynb) - notebook
* [go_analysis.pdf](go_analysis.pdf) - PDF-version

## Key Insights

* **The "Yose" Gap.** Matches against slightly stronger peers are lost in the final stage (Yose) by a tiny margin of -1.3 points. I need to polish my endgame to break through

* **Morning Peak.** Early sessions show a bolder tactical style and higher win rates. In the afternoon, my play becomes too cautious

* **Fischer Advantage.** Playing with a time increment (Fischer) boosts my performance by 9%, reducing the "panic factor" of a ticking clock

* **Defensive Resilience.** The data confirms a **"Protective" playstyle**. I am highly efficient at punishing mistakes as White (Defender), but struggle to dictate the pace when playing as Black (Attacker)
