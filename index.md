---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: main
title: Home
---

<div class="abstract">
    <p>
    I am a Ph.D. candidate at the Graduate School of Systems Information Science in <a href="https://www.fun.ac.jp/en/">Future University Hakodate</a>, Japan. I am a Japanese Government (MEXT) scholar under the supervision of <a href="http://www.fun.ac.jp/~sumi/">Prof. Yasuyuki Sumi</a> in the Interaction Media Lab. Concurrently, I am an Assistant Professor of Computer Science in the College of Computer Studies at <a href="https://www.dlsu.edu.ph/">De La Salle University</a>, Philippines. There, I founded the <a href="http://comet.dlsu.edu.ph">Center for Complexity and Emerging Technologies (COMET)</a> and is now the head of its Civic Services group.
    </p>

    <p>
    My <a href="/research/">research</a> focuses on the integration of human-computer interaction and complex systems research in developing civic solutions. For my PhD, I'm exploring novel navigation and wayfinding applications and interaction techniques for connected drivers and commuters that can influence their mobility patterns towards more livable and sustainable cities.
    </p>

    <p>
    Outside of my PhD program, my <a href="/research/">research</a> spans a broad range of topics in complex systems, human-computer interaction and civic computing, including: reflective spaces, transportation, collaboration and social networks, crowd dynamics, multi-criteria modeling and optimization, and civic solutions for mobility, transportation, and disaster awareness and preparedness. For more detailed information, please see the full-text versions of my <a href="/publications/">publications</a> and my latest <a href="/bio/">curriculum vitae</a>. If you are interested to collaborate, please contact me via email -- {{site.email}}.
    </p>

    <h4>Latest Projects</h4>
    <div class="projects">
        <div class="project">
            <img class="project-img" src="../assets/png/selected-projs/navigation.png" alt="Navigation behavior studies">
            <div class="project-desc">
                <p><span class="project-desc-main">Driver navigation behavior</span> studies to inform effective navigation application design.</p>
                <p>Papers &#187; <a href="/files/2019samson_exploringfactors_chi19.pdf">CHI'19</a></p>
                <p>Projects &#187; Navigo</p>
            </div>
        </div>

        <div class="project">
            <img class="project-img" src="../assets/png/selected-projs/apps.png" alt="Navigation apps">
            <div class="project-desc">
                <p><span class="project-desc-main">Navigation, transport and wayfinding applications</span> for sustainable mobility.</p>
                <p>Papers &#187; <a href="/files/2018samson_taxidash_mobicase.pdf">MobiCASE'18</a></p>
                <p>Applications &#187; <a href="https://taxidash.herokuapp.com/discover">TaxiDash</a></p>
            </div>
        </div>

        <div class="project">
            <img class="project-img" src="../assets/png/selected-projs/transport.png" alt="Transportation studies">
            <div class="project-desc">
                <p><span class="project-desc-main">Interactive visualization and optimization tools</span> for transportation planning.</p>
                <p>Papers &#187; <a href="/files/2018samson_gridlock_iccs.pdf">ICCS'18</a>, <a href="/files/2017samson_swarm_iccs.pdf">ICCS'17</a>, <a href="/files/2017samson_mrtmodel_pcsc.pdf">PCSC'17</a></p>
                <p>Projects &#187; Gridlock, TranspoDesire, Swarm</p>
            </div>
        </div>
    </div>

    <h4>Past Projects</h4>
    <div class="projects">
        <div class="project">
            <img class="project-img" src="../assets/png/selected-projs/pheno.png" alt="Plant phenotyping tools">
            <div class="project-desc">
                <p><span class="project-desc-main">Plant phenotyping tools</span> using computer vision techniques.</p>
                <p>Papers &#187; <a href="/files/2018constantino_chap_seight.pdf">M2VIP'15a</a>, <a href="/files/2018buzon_chap_luntian.pdf">M2VIP'15b</a></p>
            </div>
        </div>

        <div class="project">
            <img class="project-img" src="../assets/png/selected-projs/nlp.png" alt="Knowledge extraction tools">
            <div class="project-desc">
                <p><span class="project-desc-main">Knowledge extraction and language processing</span> tools for building ontologies and summarizing Philippine texts.</p>
                <p>Papers &#187; <a href="/files/2014samson_conceptrel_pkaw.pdf">PKAW'14</a>, <a href="/files/2015collantes_simpatico_nnlprs11.pdf">NNLPRS'11</a>, <a href="/files/2009samson_thematicrole_paclic.pdf">PACLIC'09</a></p>
            </div>
        </div>

        <div class="project">
            <img class="project-img" src="../assets/png/selected-projs/cbms.png" alt="Visualizing commmunity data">
            <div class="project-desc">
                <p><span class="project-desc-main">Interactive visualization tools</span> for analyzing community-based monitoring data.</p>
                <p>Papers &#187; <a href="/files/2016marcos_cbmstool_dlsurc.pdf">DLSURC'16</a>, <a href="/files/2014marcos_cbmsviz_dlsurc.pdf">DLSURC'14</a></p>
            </div>
        </div>
    </div>
</div>

<div class="news-sidebar">
    <img class="profile" src="../assets/jpg/profile.jpg" alt="Profile">

    <h4>News</h4>
    <ul class="sidebar-items">
        {% for item in site.data.news %}
            <li>{{ item.date }}: {{ item.text }}</li>
        {% endfor %}
    </ul>

    <br>
    <h4>Upcoming Talks & Travels</h4>
    <ul class="sidebar-items">
        {% for item in site.data.travels %}
            <li>{{ item.date }}: {{ item.text }}</li>
        {% endfor %}
    </ul>
</div>