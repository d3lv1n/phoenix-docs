# Phoenix Roadmap

```
Last update: 08.09.2024
```
{: .info }


## What we did so far

| Year | Our Work, Focus & Publications |
|------|--------------------------------|
| 2016 | The project is started by Flosha under the working title *Nyx*. logx joins the team. Founding of [PhoenixTales](https://phoenixtales.de). Story-writing is started. |
| 2017 | Flosha re-models the entire Old Camp of the Sequel based on Screenshots. |
| 2018 | The first version of the story of Act II is completed. |
| 2019 | We realise the work is impossible to pull off without really being able to comprehend all the material in question. Flosha sets up the Gothic Archive as an internal archive for Phoenix for the sighting of Pre-Release material; he then decides to make it public in form of a website for the community. Arbax joins the team. Pixel by pixel reconstruction of the original Gothic Alpha Ingame Font by Flosha. |
| 2020 | Release of the [Gothic Archive](https://gothicarchive.org) (v0.5) in March 21th. Gothic v0.56c and v0.64b are handed over to PhoenixTales. We publish the Phoenix Pitch from 1997. We release an updated version of the Gothic MDK. Flosha writes a new website of the project under [phoenixthegame.com](https://phoenixthegame.com) and sets Phoenix to be the new name of the project. It is published at December 24th. [Avallach joins the team?] |
| 2021 | Flosha [visits Mike Hoge](), who hands over all of his remaining design concepts for digitisation, which Piranha Bytes wanted to throw away. We release them in the archive from march 15th to april 15th. Among them hundreds of unreleased concept arts, handwritten design documents and an entire [Gothic Novel]() by Alex Wittmann, once supposed to be released as an official book. Another former developer sends us the "Phoenix Main Mission" document. Reconstruction of the original Alpha Fonts by Pierre. Creation of diverse lacking transitional textures. Tweaking of the camera perspectives. First attempt to harmonise the Alpha Troll Canyon with a Pass and the "Saturas hill". Mage's Chapel Overhaul. Baron's house overhaul. Arena overhaul. First implementation of the northern forest. The overhaul of the southern environment of the Colony begins. Overhaul of the marketplace. Implementation of a new body & head texture system by Sasha (jr) to enable us to use a more systematic naming scheme and make character individualisation easier. Implementation of FogZones by Pierre. Avallach writes a new Archive backend split in several repos to improve the very long page building loading times and enable a simple download of the Archive | 
| 2022 | We are given the Story v3.3 documentation and an additional collection of 14 Phoenix documents. They are released in the Archive at June 27th. The Mad Scientists provide us with the [Finster Demo](). We make it work on modern systems and release it in the Archive three months later in Septembre 17th. |
| 2023 | Flosha and Avallach visit Mike again to return the design documentation. We publish the Gothic Comic and are given the original Comic pencil drawings. Flosha decides to realise the Phoenix Documentation in a similar way as the Gothic Archive, as a public website to facilitate contributions, exchange of ideas and the conservation of our gamedesign ideas. The [Phoenix Concept](/) website goes online at May 14th. |
| 2024 | The model on the city and its environment continues. The focus lies completely on the design documentation and the transfer of all of our chaotic design notes in a clear and structured way into the public Phoenix Concept (except for the plot documentation, which is written in a private repo). The current leveldesign focus is on the northern environment of the colony. |
| 2025+ | Pre-Alpha Demo |
 

## Priorities

We will list our priorities split into different areas.

* **Documentation:** We try to rewrite, translate (from German to English) and bring over all the design documents written since 2016 into our public Phoenix Concept as well as finishing all the required additional research that we have to do due to the plethora of design documents we received; the study and documentation and especially harmonisation of which is taking a lot of time. This work is done by Flosha. 

* **Modeling:** In the modeling the colony has priority over the outside world and the city. The main focus of the modeling in the colony is now the northern environment, where we aim to harmonise a lot of contradictory ideas. Then we will go back to the southern environment where we need to fix and improve upon a few things. The rock cemetary and the area around the Free Camp is almost finished, but also requires tweaking and more details. At the end we will approach the overhaul of the East with the new swamp as imagined in the Alpha concepts. As for the camps: The Old Camp is almost finished except for details at the Barons house and the three additional prison levels. The New Camp model is almost done but mapping remains. The Free Camp may be done 50%. The Psi Camp is at the stage of the 0.64b Alpha, but requires additional work based on Ralfs concept arts. The outline of the city and the basic locations are set, but due to all the planned verticality, due to the necessity of making every single building theoretically accessible and so on, the remaining work load is still immense. Most work went into the Varantinian quarter (maybe done to 30%) and the Slums so far which may be done to 60-70%. The ghost district and the older parts of the city are still very barebones. The Abandoned Factory is done to ~80%. The forest modeling has not been started other than its vast outside shape. The ricefields at the city are at 10%. This work is also done by Flosha. 

* **Programming:** We want to release a first Pre-Alpha Demo focused on Item Handling, Inventory, our Modular Armour Illusion System and general movement controls in a testlevel. Auronen is working on this. But due to lack of time help of additional passionate programmers may be needed.

* **Scripting:** There is no scripting to do before the world is modeled completely. 

---

TODO:
1. When did I reconstruct the western plateau?
2. When did I reconstruct the monastery ruins?
3. When did I start modeling the city?
4. When did I decide to include the city in Act 2?
5. When did I decide to make it a single drama?
6. What did we write when in 2016-2019?
7. When did logx leave? 
8. ...


{: .roadmap }


<style>

    .roadmap {
        border: 5px solid var(--swamp);
    }


    .article ul {
        padding-left: 0;
    }

    .article ul li {
        background: var(--water);
        border: 6px solid var(--water);
        list-style: none;
        padding: 0.5em 1.5em;
        margin-bottom: 1em;
        font-size: 14px;
        font-family: monospace;
    }

        .article ul li:nth-of-type(even) {
            border: 6px solid var(--darkblood);
            background: var(--darkblood);
        }

        .article ul li strong {
            font-weight: normal;
            text-transform: uppercase;
        }

    

    .article table {
        max-width: 100%;
        font-size: 14px;
        margin: 2em 0;
        padding: 1em;
        overflow: auto;
    }

    table, th, td {
        /* border: 1px solid var(--stone);*/
        border: none;
        border-collapse: collapse;
        padding: 1em;
    }

    table tr td:nth-of-type(odd) {
        background: var(--water);
        text-align: center;
        font-family: monospace;
    }

    td {
        overflow: auto;
    }

    th {
        background: var(--darkblood);
        font-family: monospace;
        text-transform: uppercase;
        font-weight: normal;
        font-size: 14px;
    }

    tr:nth-of-type(odd) {
        background: var(--darker);
    }

    tr:nth-of-type(even) {
        background: var(--darkest);
    }
    

</style>