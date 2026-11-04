
## 2023 internal conference
- [main presentation link](https://cityandguilds-my.sharepoint.com/:u:/p/stephen_price/IQCga465K8aLQZkc8id2yRp3ASRLRp9rpDetxnv4mTEWbgA?e=VMmoo7)

## Shift in the tide

- e.g. [How backlash against data centres could shape the US midterm elections](https://www.bbc.co.uk/news/articles/c0rezqpnekro)

## Cost and control

- e.g. [Revolut cuts AI coding costs by 90 per cent via self-hosting GLM](https://techgig.com/news/ai/revolut-cuts-ai-coding-costs-by-90-per-cent-via-self-hosting-glm/135517042)

## Open? Hello China

- [Open-Source LLM Landscape 2026: What's Actually Open](https://codersera.com/blog/open-source-llms-landscape-2026/)

## Fight back

- [Technical Responses to AI](https://builtin.com/artificial-intelligence/anti-ai)
- [Codeberg](https://docs.codeberg.org/getting-started/what-is-codeberg/#what-is-codeberg-e.v.%3F)
- [Protecting our FLOSS commons from LLMs](https://blog.codeberg.org/protecting-our-floss-commons-from-llms.html)

> we believe that these technologies are incompatible with responsibly creating and maintaining free & open source software

    + [Please stop externalizing your costs directly into my face](https://drewdevault.com/blog/Stop-externalizing-your-costs-on-me/): "If you think these crawlers respect robots.txt then you are several assumptions of good faith removed from reality. These bots crawl everything they can find, robots.txt be damned, including expensive endpoints like git blame, every page of every git log, and every commit in every repo, and they do so using random User-Agents that overlap with end-users and come from tens of thousands of IP addresses – mostly residential, in unrelated subnets, each one making no more than one HTTP request over any time period we tried to measure – actively and maliciously adapting and blending in with end-user traffic and avoiding attempts to characterize their behavior or block their traffic."
    + Strained servers due to nonsensical crawling
    + The development team of none: "it seems ridiculous to see projects with a single developer and virtually no users consuming as much or even more resources than some of the largest community projects on Codeberg, which operate frugal with CI/CD and storage resources. We do not believe it is reasonable for Codeberg to invest our precious donation money into hosting of large ghost projects."
    + Hardware sourcing is becoming an headache: "Small and even large operators are endangered by rising costs, while only the largest cloud companies have reliable agreements for hardware...Devices with little compute and storage capacity take away sovereignty from users and move them into the cost trap of cloud providers selling those back to you."
    + Civic infrastructure and the environment: "Due to the energy and water demands that are inherent to the data centers built specifically for training LLMs, many communities already today experience rising consumer costs for both electricity and drinking water. And beyond the rising costs, those living close to the data centers are directly affected by increasing air and noise pollution."
    + "by adopting LLMs people tend to code single-use software from scratch"
    + 'license laundering', where copyleft code is stripped of its reciprocity requirements by 'generating' it out of the training data
    + PR burden: large PRs on open source projects that place significant burden on maintainers
    + 'transaction cost' of collaboration has increased

> we will not actively support or engage in the creation of LLMs and will not put our limited resources to use for storing single-use software that would pollute our FLOSS commons

    + Evolving terms - will be waving goodbye to the following:
        * Projects that are created by LLM "agents" in autonomous ways
        * Projects written and maintained with heavy use of LLMs
        * Projects where the amount of resources (e.g. storage, CI/CD) is significantly larger than what the involved amount of people could have created by hand
        * Projects heavily tied to the LLM ecosystem, e.g. LLM-written tools to ease LLM usage
        * Users sending LLM contributions in violation of project's custom policies
