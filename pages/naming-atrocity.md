---
title: "Naming Atrocity: Who Decides What Counts As Genocide, And Why It Matters"
layout: page
permalink: /clusters/naming-atrocity.html
---

# Heritage, Naming Atrocity
[image]

## Statement of Pedagogical Intent
The 1948 Genocide Conventions, a response to the horrors of the Holocaust, attempted to codify a global commitment to preventing such atrocities to happen again. The term “genocide” was intended to be the rallying cry that would make the world take immediate action against the party committing it. This has rarely been the case. In engaging with the materials in this cluster, students will explore the legal definition of genocide by the UN and the international community’s obligation to “prevent and punish the crime of genocide,” using this as a basis to explore how these principles actualized during the Rwandan Genocide. With findings of genocide substantiated by human rights watchdog and international organizations in mind, students will then examine if a similar situation is unfolding in Gaza. Students can further contrast the driving factors of American inaction in Rwanda versus Gaza. Overall, this set of materials aims to convey the interplay between national political interests and the weak enforceability of international law, and explores how personal and national interests can supersede international law and morality. Students engaging with these materials will gain a new perspective on how international law plays out in reality and gain a deeper geopolitical understanding of our world.

## Discussion Questions
1. 	The Genocide Convention specifically defines genocide in very narrow terms, emphasizing intent as much as consequence. How is this different from Lemkin’s original definition? How does this narrow legal definition shape when and whether actors, including states and organizations, are willing to label a situation as genocide, and what are the consequences of that threshold being so difficult to meet?
2. 	US officials repeatedly avoided using the term “genocide” during the Rwanda genocide, instead opting for “acts of genocide.” Why? What legal, political, and public consequence does the term “genocide” carry? Can/should a state avoid those responsibilities by merely not labeling something as “genocide”?
3. 	On June 10, 1994, spokesperson for the State Department Christine Shelly was asked by Reuters correspondent Alan Elsner: “How many acts of genocide does it take to make a genocide?” to which Shelly responded: “Alan, that’s just not a question I’m in a position to answer.” Who is in the position to answer? Who can define a genocide, and what power do they wield? Thinking more broadly, what is the power dynamic between international organizations like Amnesty International or Human Rights Watch and national governments?
4. 	What are the similarities and differences between each of the three genocide definitions (UN, Lemkin, and LeVine)? What is the rationale behind their differences? How can different definitions of the term impact real-world events?

## In-class Activity
Here are some additional sources to supplement discussion that students can explore in class as a collective:
1. 	<a href="https://www.youtube.com/watch?v=CBfRWq0Sbhs"> 40 second video detailing Shelly’s exchange with Elsner in 1994 </a>
2. 	Recent developments: <a href="https://www.commondreams.org/news/icj-us-israel"> USA joins Israel in defending against South Africa claims of genocide </a>  
In-class discussion: What do you think the term “genocide” should mean? What aspects of Lemkin’s and/or the UN’s definition do you agree or disagree with, and why?
        	This lends itself very well into in a class word-map, where students can put phrases/concept that they believe constitute the definition of genocide.
Additional question: What do you think the definition of genocide should be?
In-class discussion two: Amnesty International and other international organizations have <a href="https://www.amnesty.org/en/latest/news/2024/12/amnesty-international-concludes-israel-is-committing-genocide-against-palestinians-in-gaza/"> concluded that Israel is conducting genocide in Gaza. </a> What response has this elicits from the public and national government? How do you feel about this (i.e. is their definition accurate? Do you believe them?). How does this change international discourse on the Israel-Palestine conflict?


## Accessibility Statement
Accessiblity Statement

## Sources
<div class="row mb-2">
    <div class="col-7 col-lg-9">{{ content }}</div>
    <div class="col-5 col-lg-3 text-end text-lg-start">{% if site.data.theme.advanced-search == true %}{% include advanced-search-modal.html %}{% endif %}</div>
</div>
<div class="row mb-3 justify-content-center">
    <div class="col-lg-8 text-center">
        <form role="search" id="browseFilter" onsubmit="submitFilter(); return false;">
            <div class="input-group input-group-lg">
                {% if site.data.theme.faceted-search == true %}
                <select class="form-control form-select d-none d-lg-block" id="fieldSelect" style="max-width: 200px;" aria-label="select search field to filter">
                    <option value="all">All Fields</option>
                    <option value="title">Title</option>
                    {% for f in fields %}
                    {% assign cap-field = f.field | capitalize %}
                    <option value="{{ f.field }}">{{ f.facet_name | default: f.display_name | default: cap-field }}</option>
                    {% endfor %}
                    <option value="display_template">Content Type</option>
                    {% if site.data.theme.advanced-search == true %}
                    <option value="" disabled>─────────────</option>
                    <option value="advanced">Advanced Search...</option>{% endif %}
                </select>
                <!-- Mobile filter button - shows only on small screens -->
                <div class="{% if site.data.theme.faceted-search == true %}dropdown d-lg-none{% else %}d-none{% endif %}">
                    <button class="py-3 btn btn-outline-secondary" type="button" id="mobileFilterButton" data-bs-toggle="dropdown" aria-expanded="false" title="Filter options">
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-funnel" viewBox="0 0 16 16">
                            <path d="M1.5 1.5A.5.5 0 0 1 2 1h12a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-.128.334L10 8.692V13.5a.5.5 0 0 1-.342.474l-3 1A.5.5 0 0 1 6 14.5V8.692L1.628 3.834A.5.5 0 0 1 1.5 3.5v-2zm1 .5v1.308l4.372 4.858A.5.5 0 0 1 7 8.5v5.306l2-.666V8.5a.5.5 0 0 1 .128-.334L13.5 3.308V2h-11z"/>
                        </svg>
                        <span id="selectedField" class="d-none d-sm-inline ms-1">All Fields</span>
                    </button>
                    <div class="dropdown-menu">
                        <button class="dropdown-item" type="button" data-field="all">All Fields</button>
                        <button class="dropdown-item" type="button" data-field="title">Title</button>
                        {% for f in fields %}
                        {% assign cap-field = f.field | capitalize %}
                        <button class="dropdown-item" type="button" data-field="{{ f.field }}">{{ f.facet_name | default: f.display_name | default: cap-field }}</button>
                        {% endfor %}
                        <button class="dropdown-item" type="button" data-field="display_template">Content Type</button>
                        {% if site.data.theme.advanced-search == true %}
                        <div class="dropdown-divider"></div>
                        <button class="dropdown-item" type="button" data-field="advanced">Advanced Search...</button>
                        {% endif %}
                    </div>
                </div>{% endif %}
                <input type="text" class="form-control" id="filterTextBox" placeholder="Filter ... " aria-label="Search"> 
                <!-- Update the date range inputs section -->
                <div id="dateRangeInputs" class="date-range-inputs">
                    <div class="date-input-group">
                        <input type="text" id="startDate" class="ms-2 form-control" placeholder="Start Date">
                        <span class="date-separator">to</span>
                        <input type="text" id="endDate" class="me-2 form-control" placeholder="End Date">
                    </div>
                </div>
                <button class="btn btn-success" type="submit" title="Filter items" id="filterButton" >Search</button>
                <button class="btn btn-outline-secondary filter d-none d-lg-flex" onclick="resetFilter(); return false;" data-filter="">Reset</button>
            </div>
        </form>
        <!-- Active filter indicators -->
        <div id="activeFilters" class="mt-2 text-start"></div>
        <div class="h2" id="numberOf"></div>
    </div>
    <div class="col-lg-2">
        <div class="dropdown">
            <button class="btn btn-secondary mt-1 dropdown-toggle" type="button" id="browseSortButton" data-bs-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                Sort by <span id="sortFilter">Random</span>
            </button>
            <div class="dropdown-menu browse-sort-menu" aria-labelledby="browseSortButton">
                <button class="dropdown-item browse-sort-item {% if site.data.theme.default-sort-field == '' %}active{% endif %}" data-filter="random">Random</button>
                <button class="dropdown-item browse-sort-item" data-filter="title">Title</button>
                {% assign sort_options = site.data.config-browse | where_exp: 'i','i.sort_name != nil' %}
                {% for o in sort_options %}
                <button class="dropdown-item browse-sort-item" data-filter="{{ o.field | escape }}">{{ o.sort_name }}</button>
                {% endfor %}
            </div>
            <button class="btn btn-outline-secondary filter p-1 d-lg-none float-end" onclick="resetFilter(); return false;" data-filter="">Reset</button>
        </div>
       
    </div>
</div>

<div id="loadingIcon" class="text-center">
    <div class="spinner-border text-dark" role="status"><span class="visually-hidden">Loading...</span></div>
</div>

<div class="row" id="browseItems"></div>
