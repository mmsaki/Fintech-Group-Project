 <img src="https://pbs.twimg.com/media/FRT011vVUAAE0iF?format=jpg&name=4096x4096" alt="Beeple Art" width="100%"/>


## Table of Contents

1. [Project Summary](#1-project-summary)
2. [Hypothesis](#2-hypothesis)
3. [Data Collection & Cleanup](#3-data-collection--cleanup)
4. [Analysis](#4-analysis)
5. [Postmoterm](#5-postmoterm)
6. [Discussion](#6-discussion)
7. [Contributors](#7-contributors)

## 1. Project Summary
* Our project uncovers patterns in NFT trading for three NFT collections.
    * Part One : [Boyed Ape Yatch Club](https://boredapeyachtclub.com/)
    * Part Two : [Azuki](https://www.azuki.com)
    * Part Three : [Cryptopunks](http://larvalabs.com/cryptopunks)
* We'll examine relationships between types of:
    * Historical Volume 
    * Purchase prices
    * Trends in sales over the recent 1000 transactions
    * Other transaction data ie. total transaction fees paid for all collections

## 2. Hypothesis
* Should you invest in Azuki, BAYC or Crypto Punks? 
    * What are people paying for NFT in USD value?
    * How much in fees are being paid per transaction?
    * Is the value appreciating or declining?
* How can you tell which collection is performing well?
    * What is the daily transaction volume after Collection is released?

## 3. Data Collection & Cleanup
* How do we collect NFT data?
    - [x] Covalent APIs
    - [x] Etherscan API
    - [x] Other Dependancies ie. Plotly Express
    ![APIs and Imports](./exports/png/nft_analysis.png)
* Why cleanup data?
    * Prepare data for analysis
    * Isolate the types of data we are interested in from the rest
    * See what the customer data look like
    * Evaluate performance

## 4. Analysis

* What kind of data we like to work with and the field we're interested in 

    ![](./images/azuki_girl44.png)
- [x] Part One: Azuki

    ![Daily volume Analysis](./exports/png/nft_analysis_pg2.png)

    ![Daily Volume Azukis](./exports/azuki_daily_volume.png)
    ![Azuki Sales](./exports/azuki_daily_sales.png)

    ![ Punks](./images/punks_pr0.png)
- [x] Part Two: Cryptopunks 

    ![Cris Punks](./images/cryptopunks_bokeh_plot.png)
    ![Chris Combined plot](./images/punks_combined_wrapped_analysis.png)
    ![Chris Cryptopunks Sales Ether](./images/cryptopunks_sales_by_ether.png)

![](./images/bored_apes.jpeg)

- [x] Part Three: Bored Ape Yatch Club

    ![Daily Volume Bored Apes](./exports/BAYC_daily_volume.png)
    ![Ape Sales](./exports/BAYC_daily_sales.png)

- [x] Historical sales recent 1000 transactions
    ![Historical sales Analysis](./exports/png/nft_analysis_pg6.png)


- [x] Total fees paid comparison
    ![Fees Comparison](./exports/fees_paid_comparison.png)

- [x] Comparing Collections performance
    ![Comparing Collections performance](./exports/Volume_sales_recent_1000.png)


## 5. Postmoterm
* Did we find everything we expected to find?
    - [x] What are our difficulties 
    - [x] How did we deal with them
    - [x] Additional questions that came up
    - [x] What would we research next if we had more time?

## 6. Discussion

* After we've analyzed our data to our satisfaction, we'll put together a presentation to show off our work, explain our process, and discuss our conclusions.
* This presentation will be delivered as a slideshow, and it would give our classmates and instructional staff an overview of our work. 

**File:** [Analysis](./project_analysis_2.0.ipynb) <br>
**File:** [Project Presentation](./exports/pdf/group_presentation.pdf)

![](./exports/project_analysis_2.0.png)
## 7. Contributors 

- [@mmsaki](https://github.com/mmsaki)
- [@dockingbay24](https://github.com/dockingbay24)
- [@angel-estrada7](https://github.com/angel-estrada7)
