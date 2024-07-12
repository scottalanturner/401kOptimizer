<a id="readme-top"></a>




<!-- PROJECT SHIELDS -->

[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/scottalanturner/Optimize-401k">
    <img src="images/logo.png" alt="Logo">
  </a>

<h3 align="center">OPTIMIZE 401k</h3>

  <p align="center">
    A tool to help fix broken 401ks
    <br />
    <a href="https://github.com/scottalanturner/Optimize-401k"><strong>Explore the docs »</strong></a>
    <br />
    <br />
     <a href="https://github.com/scottalanturner/Optimize-401k/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    ·
    <a href="https://github.com/scottalanturner/Optimize-401k/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
    
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

<b>One liner</b> - Take all of a person's current investments (stocks, bonds, mutual funds, cash, multiple account types) and show how to rebalance/reallocate them to a 60/40 portfolio. <i>(You can define your own output portfolio).</i>

After counseling hundreds of people on their finances and investments, I kept seeing the same mistakes over and over in retirement accounts. Too much risk, too little risk, too much overlap, making investment choices that made no sense. Only once did I find a person who didn't need any changes after they sent me their retirement account statement. They happened to have been listening to my talk show for years and had already implemented my suggestions.

The problem is when it comes to retirement accounts, there is no cookie cutter advice that gives the best results. Roboadvisors are a good tool, but they don't look at things holistically. Most financial planners have $500,000 minimums to work with them. Most of the brokerages have people you can talk to (sometimes a CFP), but they have the same problem of looking at investments as a silo. I love me some taxes (researching them, not paying them), and often the biggest wins are by optimizing tax buckets, not investment buckets.

So I created a service that focused just on 401(k)s (or any employer retirement account). After a couple of trial users I realized I needed way better software to work efficiently. 

This project is different than other types of investment projects, which all seem to focus on individual stocks from Microsoft, Apple, Google, whatever your neighbor told you to buy, etc. Most employers have a basket of mutual funds, of equities and fixed income. That's what we analyze here.

I rarely saw a person who had a single account. The sample dataset here has several IRAs, from different owners, and a brokerage account. That's typical of most clients. If everything isn't considered holistically, most likely money is being lost, or will be lost come tax time decades down the road when it's too late to fix.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* ![Jupyter Notebook-compatible](https://img.shields.io/badge/Jupyter%20Notebook-compatible-2ea44f?style=for-the-badge&logo=jupyter)


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Download the two Excel files. Try them out first with the sample data, then fill them in with your own data.

### Prerequisites

Aside from the standard data science libraries (pandas, numpy, scikit-learn, seaborn, matplotlib) you will need to install (with conda or pip):
* yfinance - to pull down fund/stock history
  ```sh
   conda install yfinance
  ```
* plotly.express - For some awesome sunburst charts
  ```sh
   conda install plotly.express
  ```

### Installation

1. Your favorite platform to run a jupyter notebook

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

There are two (2) Excel files used for input.

1) 60-40-Vanguard Portfolio - This is a list of tickers/allocation percentages for a 60/40 portfolio using Vanguard funds. They can be any funds or percentages. A future revision would be to have one Portfolio file with all portfolios in use, and a keyword to pull just those into the notebook.

2) 401k-client-data - The clients current portfolio to analyze.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

No warranty is made with respect to the accuracy or completeness of the information contained herein. It should not be considered financial advice. And finally - past performance does not guarantee future performance!

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Scott Alan Turner - [scott@scottalanturner.com](mailto:scott@scottalanturner.com)

Project Link: [https://github.com/scottalanturner/Optimize-401k](https://github.com/scottalanturner/Optimize-401k)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[issues-url]: https://github.com/scottalanturner/Optimize-401k/issues
[license-shield]: https://img.shields.io/github/license/scottalanturner/Optimize-401k.svg?style=for-the-badge
[license-url]: https://github.com/scottalanturner/Optimize-401k/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/scottalanturner
[product-screenshot]: images/screenshot.png
