---
layout: default
title: "Home"
---

<!-- Hero -->
<section class="relative p-12">
    <img class="absolute z-[-1] top-[20px] left-[-80px] scale-95" src="./assets/img/background-shapes/hero-bg.svg"
        alt="">
    <div class="flex justify-start items-center py-48 pt-32">
        <div class="inner--large">
            <h1>Open Work <br>Definition</h1>
            <p class="text-2xl">Subtitle will be place here with 36 pt <br>regular weight.</p>
            <button class="mt-6 mb-12">Request Edit</button>
            <p class="text-xs">This project is maintained by Open@RIT<br>Hoston on GitHub Pages</p>
        </div>
    </div>
</section>

<hr class="section-divider bg-black border-none h-[2px] mt-[1rem]">

<!-- Goal of Open Work -->
<section class="relative p-12 lg:grid grid-cols-2 justify-center inner--small gap-12">
    <img class="absolute z-[-1] top-[-30%] left-[-14%] max-w-[80rem]"
        src="./assets/img/background-shapes/open-work-goal-bg.svg" alt="">
    <div class="">
        <h2 class="sm:whitespace-nowrap">Why Are We Using The Term <br><b>Open Work</b>?</h2>
        <p class="subtitle">Goal of Open Work</p>
        <hr class="subtitle-divider">
        <p>People produce and collaborate on all different types of work within academia and beyond. Different types of
            works can be released and developed among communities of practice in different ways.
            <br><br>
            To treat each type of Open Work as its own silo hinders the ability for these works to be used
            interchangeably among each other.
            <br><br>
            We use the term Open Work to talk about a larger theory of practice in which Works of all types are
            developed, distributed, and collaborated upon.
        </p>
    </div>
    <img class="place-self-end" src="./assets/img/illustrations/goal-of-open-work.svg" alt="">
</section>

<hr class="section-divider">

<!-- Definition of Open Work -->
<section class="relative p-12">
    <img class="absolute z-[-1] scale-125 top-20" src="assets/img/background-shapes/open-def-bg.svg" alt="">
    <h2 class="text-center mb-20"><b>Open Work</b> Definition Version 0.1</h2>
    <div class="inner--small flex justify-center flex-col m-auto">
        <img src="./assets/img/illustrations/browser-window.svg" alt="">
        <img class="mt-[-6rem]" src="./assets/img/illustrations/three-people-talking.svg" alt="">
    </div>

    <!-- accordions from tw-elements library -->
    <div class="mt-20 max-w-lg m-auto accordion space-y-6" id="accordionCol1">
        <div class="accordion-item bg-[#F2F2F2] rounded-xl">
            <h2 class="accordion-header mb-0" id="headingOne">
                <button class="accordion-button accordion-button--gray collapsed h-[4.4rem]" type="button"
                    data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="false"
                    aria-controls="collapseOne">
                    <img class="mr-4 w-12" src="./assets/img/icons/documents-2.svg" alt="">
                    Definition of Work
                </button>
            </h2>
            <div id="collapseOne" class="accordion-collapse collapse" aria-labelledby="headingOne"
                data-bs-parent="#accordionCol1">
                <div class="accordion-body py-4 px-5">
                    A <b>Work</b> is any piece of copyrightable material. This could be software, writing, music, and
                    many other things.
                    <br><br>
                    <a href="">See below</a> for common types of Open Works.
                </div>
            </div>
        </div>
        <div class="accordion-item bg-[#F2F2F2] rounded-xl">
            <h2 class="accordion-header mb-0" id="headingTwo">
                <button class="accordion-button accordion-button--gray collapsed" type="button"
                    data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false"
                    aria-controls="collapseTwo">
                    <img class="mr-4 w-12" src="./assets/img/icons/no-copyright.svg" alt="">
                    Definition of License
                </button>
            </h2>
            <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo"
                data-bs-parent="#accordionCol1">
                <div class="accordion-body py-4 px-5">
                    A <b>License</b>, in this context, is a document describing the terms and conditions that one is
                    allowed to use a <b>Work</b>.
                    <br><br>
                    A <b>License</b> is necessary for any <b>Work</b> to be considered
                    <b>Open</b> unless that work is <b>Public Domain</b>.

                </div>
            </div>
        </div>
        <div class="accordion-item bg-[#F2F2F2] rounded-xl">
            <h2 class="accordion-header mb-0" id="headingThree">
                <button class="accordion-button accordion-button--gray collapsed" type="button"
                    data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false"
                    aria-controls="collapseThree">
                    <img class="mr-4 w-12" src="./assets/img/icons/documents.svg" alt="">
                    Definition of Open
                </button>
            </h2>
            <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree"
                data-bs-parent="#accordionCol1">
                <div class="accordion-body py-4 px-5">
                    As with most definitions of Open, our definition specifically focuses on the licensing and
                    redistribution of a Work. That work must be available and licensed so anyone can view it,
                    redistribute it, and modify it openly, in compliance with whatever license has been applied to it.
                    <br><br>
                    For more details on the exact definition of Open - See the <a
                        href="http://opendefinition.org/od/2.1/en/">OKF's definition of “Open.”</a>
                </div>
            </div>
        </div>
        <div class="accordion-item bg-[#F2F2F2] rounded-xl">
            <h2 class="accordion-header mb-0" id="headingFour">
                <button class="accordion-button accordion-button--gray collapsed" type="button"
                    data-bs-toggle="collapse" data-bs-target="#collapseFour" aria-expanded="false"
                    aria-controls="collapseFour">
                    <img class="mr-4 w-12" src="./assets/img/icons/no-copyright-2.svg" alt="">
                    Definition of Public Domain
                </button>
            </h2>
            <div id="collapseFour" class="accordion-collapse collapse" aria-labelledby="headingFour"
                data-bs-parent="#accordionCol1">
                <div class="accordion-body py-4 px-5">
                    When a <b>Work</b> has no copyright, it is available to the public. This means that no individual
                    has
                    any ownership over that work. A <b>Public Domain Work</b> cannot be <b>Licensed</b> as there is no
                    copyright holder.
                    <br><br>
                    <b>A Public Domain Work</b> is considered one form of an <b>Open Work</b>.
                </div>
            </div>
        </div>
    </div>

    <!-- Definition of... cards -->
    <div class="mt-28 flex flex-wrap lg:flex-nowrap space-x-0 justify-center gap-8 lg:gap-14">
        <div class="relative bg-[#F2F2F2] rounded-3xl w-[26rem] px-8 py-10 pr-16">
            <div class="flex flex-col items-start align-top">
                <p class="mb-2 font-bold"><b>Definition of Work</b></p>
                <p>A <b>Work</b> is any piece of copyrightable material. This could be software, writing, music, and
                    many other things.
                    <br><br>
                    <a href="">See below</a> for common types of Open Works.
                </p>
                <img class="absolute top-[-12px] right-[-12px] w-14" src="./assets/img/icons/documents-2.svg" alt="">
                <!-- card icon -->
            </div>
        </div>
        <div class="relative bg-[#F2F2F2] rounded-3xl w-[26rem] px-8 py-10 pr-16">
            <div class="flex flex-col items-start align-top">
                <p class="mb-2 font-bold"><b>Definition of License</b></p>
                <p>A <b>License</b>, in this context, is a document describing the terms and conditions that one is
                    allowed to use a <b>Work</b>.
                    <br><br>
                    A <b>License</b> is necessary for any <b>Work</b> to be considered
                    <b>Open</b> unless that work is <b>Public Domain</b>.
                </p>
                <img class="absolute top-[-12px] right-[-12px] w-14" src="./assets/img/icons/no-copyright.svg" alt="">
                <!-- card icon -->
            </div>
        </div>

    </div>
    <div class="flex flex-wrap lg:flex-nowrap space-x-0 justify-center gap-8 lg:gap-14 lg:space-y-8">
        <div class="relative bg-[#F2F2F2] rounded-3xl w-[26rem] px-8 py-10 pr-16 mt-8">
            <div class="flex flex-col items-start align-top">
                <p class="mb-2 font-bold"><b>Definition of Open</b></p>
                <p>As with most definitions of Open, our definition specifically focuses on the licensing and
                    redistribution of a Work. That work must be available and licensed so anyone can view it,
                    redistribute it, and modify it openly, in compliance with whatever license has been applied to it.
                    <br><br>
                    For more details on the exact definition of Open - See the <a
                        href="http://opendefinition.org/od/2.1/en/">OKF's definition of “Open.”</a>
                </p>
                <img class="absolute top-[-12px] right-[-12px] w-14" src="./assets/img/icons/documents.svg" alt="">
                <!-- card icon -->
            </div>
        </div>

        <div class="relative bg-[#F2F2F2] rounded-3xl w-[26rem] px-8 py-10 pr-16 mt-0 lg:mt-8">
            <div class="flex flex-col items-start align-top">
                <p class="mb-2 font-bold"><b>Definition of Public Domain</b></p>
                <p>When a <b>Work</b> has no copyright, it is available to the public. This means that no individual has
                    any ownership over that work. A <b>Public Domain Work</b> cannot be <b>Licensed</b> as there is no
                    copyright holder.
                    <br><br>
                    <b>A Public Domain Work</b> is considered one form of an <b>Open Work</b>.
                </p>
                <img class="absolute top-[-12px] right-[-12px] w-12" src="./assets/img/icons/no-copyright-2.svg" alt="">
                <!-- card icon -->
            </div>
        </div>
    </div>
</section>

<hr class="section-divider">

<!-- The Roots of Open Work -->
<section class="relative p-12">
    <img class="w-[100rem] absolute z-[-1] right-[-50px] bottom-[-150px]"
        src="./assets/img/background-shapes/open-work-roots-bg.svg" alt="">
    <h2 class="text-center">The <b>Roots</b> of "Open Work"</h2>
    <p class="mb-20 max-w-sm text-center m-auto">The intellectual “Family Tree” of the term Open Work includes examples
        from
        technology, science, and the arts.</p>
    <div class="inner--large lg:grid grid-cols-7 justify-center gap-4 lg:space-y-0 space-y-12">
        <div
            class="relative col-span-3 after:absolute after:hidden lg:after:block after:top-0 after:right-0 after:border-r-2 after:border-black after:h-[70%] pr-6">
            <p class="subtitle">Technology</p>
            <hr class="subtitle-divider">
            <p><a href="http://criticalartware.net/DistributionReligion/DistributionReligion.pdf">Distribution
                    Religion</a>: Arguably the first “Open Hardware” license, from the manual/instructions for the
                <a href="https://en.wikipedia.org/wiki/Sandin_Image_Processor">Sandin Image Processor</a>) (1976-1978)
                <br><br>
                <a href="https://en.wikipedia.org/wiki/Li-Chen_Wang">CopyLeft: Li-Chen Wang</a>'s Palo Alto <a
                    href="https://en.wikipedia.org/wiki/Tiny_BASIC">Tiny BASIC</a> (1976)
                <br><br>
                <a href="https://www.fsf.org/">Free Software, the FSF and the GPL: Richard Stallman</a> et al beginning
                in 1984-Present
                <br><br>
                <a href="https://opensource.com/article/18/2/coining-term-open-source-software">Open Source</a>: The
                term coined by <a href="https://opensource.com/users/christine-peterson">Christine Peterson</a> and the
                creation of the <a href="https://opensource.org/history">Open Software Initiative</a>,
                1998
            </p>
        </div>
        <div
            class="relative col-span-2 after:absolute after:hidden lg:after:block after:top-0 after:right-0 after:border-r-2 after:border-black after:h-[70%] pr-6">
            <p class="subtitle">Literature and the Arts</p>
            <hr class="subtitle-divider">
            <p>Umberto Eco's “<a
                    href="https://www.researchgate.net/publication/280730233_Text_and_Meaning_in_Umberto_Eco's_The_Open_Work">The
                    Open Work</a>” is art with “two constituents: a multiplicity of meanings and the
                participation
                of the audience."
            </p>
        </div>
        <div class="col-span-2">
            <p class="subtitle">Science</p>
            <hr class="subtitle-divider">
            <p>The intellectual “Family Tree” of the term Open Work includes examples from technology, science, and the
                arts.
            </p>
        </div>
    </div>
</section>

<hr class="section-divider">

<section class="p-12 relative pb-20">
    <img class="absolute z-[-1] scale-[1] translate-x-[-80px] top-20"
        src="assets/img/background-shapes/types-of-open-work-bg.svg" alt="">
    <!-- Types of Open Work -->
    <!-- accordions from tw-elements library -->
    <h2 class="text-center mb-14">Types of <b>Open Work</b></h2>
    <div class="sm:grid grid-cols-2 gap-16 inner--small m-auto justify-center">
        <div class="accordion space-y-6" id="accordionCol1">
            <div class="accordion-item bg-[#F2F2F2] rounded-xl">
                <h2 class="accordion-header mb-0" id="headingOne">
                    <button class="accordion-button accordion-button--gray collapsed h-[4.4rem]" type="button"
                        data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="false"
                        aria-controls="collapseOne">
                        <img class="mr-4" src="./assets/img/icons/educational-resources.svg" alt="">
                        Open Educational Resources
                    </button>
                </h2>
                <div id="collapseOne" class="accordion-collapse collapse" aria-labelledby="headingOne"
                    data-bs-parent="#accordionCol1">
                    <div class="accordion-body py-4 px-5">
                        OER are openly licensed educational materials — everything from a single lesson plan to an
                        entire
                        textbook — that are free to use, customize, and share.
                        <br>
                        <br>
                        <a href="https://www.oercommons.org/oer-101" rel="noopener noreferrer">OER
                            Commons</a>
                    </div>
                </div>
            </div>
            <div class="accordion-item bg-[#F2F2F2] rounded-xl">
                <h2 class="accordion-header mb-0" id="headingTwo">
                    <button class="accordion-button accordion-button--gray collapsed" type="button"
                        data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false"
                        aria-controls="collapseTwo">
                        <img class="mr-4" src="./assets/img/icons/innovation.svg" alt="">
                        Open Innovation
                    </button>
                </h2>
                <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo"
                    data-bs-parent="#accordionCol1">
                    <div class="accordion-body py-4 px-5">
                        "A distributed innovation process based on purposively managed knowledge flows across
                        organizational
                        boundaries, using pecuniary and non-pecuniary mechanisms in line with the organization's
                        business
                        model". <sup><a href="https://en.wikipedia.org/wiki/Open_innovation#cite_note-4">[4]</a></sup> —
                        Henry Chesbrough
                        <br>
                        <br>
                        This more recent definition acknowledges that open innovation is not solely firm-centric: it
                        also
                        includes <a href="https://en.wikipedia.org/wiki/Creative_consumer"> creative consumers</a> <a
                            href="https://en.wikipedia.org/wiki/Open_innovation#cite_note-5"><sup>[5]</sup></a> and
                        communities of user innovators. <a
                            href="https://en.wikipedia.org/wiki/Open_innovation#cite_note-6"><sup>[6]</sup></a>
                        <br>
                        <br>
                        <a href="http://openinnovation.net/about-2/open-innovation-definition/"
                            rel="noopener noreferrer">Open Innovation Community</a>

                    </div>
                </div>
            </div>
            <div class="accordion-item bg-[#F2F2F2] rounded-xl">
                <h2 class="accordion-header mb-0" id="headingThree">
                    <button class="accordion-button accordion-button--gray collapsed" type="button"
                        data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false"
                        aria-controls="collapseThree">
                        <img class="mr-4" src="./assets/img/icons/software.svg" alt="">
                        Open Source Software
                    </button>
                </h2>
                <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree"
                    data-bs-parent="#accordionCol1">
                    <div class="accordion-body py-4 px-5">
                        Open source software is code that is designed to be publicly accessible—anyone can see, modify,
                        and
                        distribute the code as they see fit.
                        <br>
                        <br>
                        <a href="https://www.redhat.com/en/topics/open-source/what-is-open-source">Red Hat, Inc.
                        </a>
                    </div>
                </div>
            </div>
            <div class="accordion-item bg-[#F2F2F2] rounded-xl">
                <h2 class="accordion-header mb-0" id="headingFour">
                    <button class="accordion-button accordion-button--gray collapsed" type="button"
                        data-bs-toggle="collapse" data-bs-target="#collapseFour" aria-expanded="false"
                        aria-controls="collapseFour">
                        <img class="mr-4" src="./assets/img/icons/scholarship.svg" alt="">
                        Open Scholarship
                    </button>
                </h2>
                <div id="collapseFour" class="accordion-collapse collapse" aria-labelledby="headingFour"
                    data-bs-parent="#accordionCol1">
                    <div class="accordion-body py-4 px-5">
                        Open Scholarship is defined by the Association of Research Libraries (ARL) as encompassing open
                        access, open data, open educational resources, and all other forms of openness in the scholarly
                        and
                        research environment, is changing how knowledge is created and shared.
                        <br>
                        <br>
                        <a href="https://guides.library.pdx.edu/c.php?g=931273&p=6711316">Portland State University
                            Library
                        </a>
                    </div>
                </div>
            </div>
            <div class="accordion-item bg-[#F2F2F2] rounded-xl">
                <h2 class="accordion-header mb-0" id="headingFive">
                    <button class="accordion-button accordion-button--gray collapsed" type="button"
                        data-bs-toggle="collapse" data-bs-target="#collapseFive" aria-expanded="false"
                        aria-controls="collapseFive">
                        <img class="mr-4" src="./assets/img/icons/data.svg" alt="">
                        Open Data/Open Knowledge
                    </button>
                </h2>
                <div id="collapseFive" class="accordion-collapse collapse" aria-labelledby="headingFive"
                    data-bs-parent="#accordionCol1">
                    <div class="accordion-body py-4 px-5">
                        A data set that is released freely for any to use and modify.
                        <br>
                        <br>
                        Open definition: <a href="https://opendefinition.org/">Open Knowledge Foundation </a>
                        <br>
                        <br>
                        Open knowledge: <a href="https://okfn.org/opendata/">Open Knowledge Foundation </a>
                    </div>
                </div>
            </div>
        </div>
        <div class="accordion mt-6 sm:mt-0 space-y-6" id="accordionCol2">
            <div class="accordion-item bg-[#F2F2F2] rounded-xl">
                <h2 class="accordion-header mb-0" id="headingSix">
                    <button class="accordion-button accordion-button--gray collapsed" type="button"
                        data-bs-toggle="collapse" data-bs-target="#collapseSix" aria-expanded="false"
                        aria-controls="collapseSix">
                        <img class="mr-4" src="./assets/img/icons/hardware.svg" alt="">
                        Open Hardware
                    </button>
                </h2>
                <div id="collapseSix" class="accordion-collapse collapse" aria-labelledby="headingSix"
                    data-bs-parent="#accordionCol2">
                    <div class="accordion-body py-4 px-5">
                        Open source hardware is hardware whose design is made publicly available so that anyone can
                        study,
                        modify, distribute, make, and sell the design or hardware based on that design.
                        <br>
                        <br>
                        <a href="https://www.oshwa.org/definition/">Open Source Hardware Association</a>
                    </div>
                </div>
            </div>
            <div class="accordion-item bg-[#F2F2F2] rounded-xl">
                <h2 class="accordion-header mb-0" id="headingSeven">
                    <button class="accordion-button accordion-button--gray collapsed" type="button"
                        data-bs-toggle="collapse" data-bs-target="#collapseSeven" aria-expanded="false"
                        aria-controls="collapseSeven">
                        <img class="mr-4" src="./assets/img/icons/science.svg" alt="">
                        Open Science
                    </button>
                </h2>
                <div id="collapseSeven" class="accordion-collapse collapse" aria-labelledby="headingSeven"
                    data-bs-parent="#accordionCol2">
                    <div class="accordion-body py-4 px-5">
                        Open science encompasses unhindered access to scientific articles, access to data from public
                        research, and collaborative research enabled by ICT tools and incentives.
                        <br>
                        <br>
                        Open definition: <a href="https://www.oecd.org/sti/inno/open-science.htm"> Organisation for
                            Economic Co-operation and Development</a>
                    </div>
                </div>
            </div>
            <div class="accordion-item bg-[#F2F2F2] rounded-xl">
                <h2 class="accordion-header mb-0" id="headingEight">
                    <button class="accordion-button accordion-button--gray collapsed" type="button"
                        data-bs-toggle="collapse" data-bs-target="#collapseEight" aria-expanded="false"
                        aria-controls="collapseEight">
                        <img class="mr-4" src="./assets/img/icons/design.svg" alt="">
                        Open Design
                    </button>
                </h2>
                <div id="collapseEight" class="accordion-collapse collapse" aria-labelledby="headingEight"
                    data-bs-parent="#accordionCol2">
                    <div class="accordion-body py-4 px-5">
                        Any piece of design work released freely for anyone to use or modify.
                        <br>
                        <br>
                        <a
                            href="https://github.com/OpenDesign-WorkingGroup/Open-Design-Definition/blob/master/open.design_definition/open.design.definition.md">Open
                            Design Working Group Definition</a>
                    </div>
                </div>
            </div>
            <div class="accordion-item bg-[#F2F2F2] rounded-xl">
                <h2 class="accordion-header mb-0" id="headingNine">
                    <button class="accordion-button accordion-button--gray collapsed" type="button"
                        data-bs-toggle="collapse" data-bs-target="#collapseNine" aria-expanded="false"
                        aria-controls="collapseNine">
                        <img class="mr-4" src="./assets/img/icons/research.svg" alt="">
                        Open Research
                    </button>
                </h2>
                <div id="collapseNine" class="accordion-collapse collapse" aria-labelledby="headingNine"
                    data-bs-parent="#accordionCol2">
                    <div class="accordion-body py-4 px-5">
                        Open research comprises openness throughout the research cycle through collaborative working and
                        sharing and making research methodology, software, code, and equipment freely available online,
                        along with instructions for using it.
                        <br>
                        <br>
                        Open research includes making publications freely available online (open access) in addition to
                        the underlying research data (open data).
                        <br>
                        <br>
                        <a href="http://www.exeter.ac.uk/research/openresearch/about/explained/">University of Exeter
                            (UK)
                        </a>
                    </div>
                </div>
            </div>
            <div class="accordion-item bg-[#F2F2F2] rounded-xl">
                <h2 class="accordion-header mb-0" id="headingTen">
                    <button class="accordion-button accordion-button--gray collapsed" type="button"
                        data-bs-toggle="collapse" data-bs-target="#collapseTen" aria-expanded="false"
                        aria-controls="collapseTen">
                        <img class="mr-4" src="./assets/img/icons/journals.svg" alt="">
                        Open Access Journals
                    </button>
                </h2>
                <div id="collapseTen" class="accordion-collapse collapse" aria-labelledby="headingTen"
                    data-bs-parent="#accordionCol2">
                    <div class="accordion-body py-4 px-5">
                        Open Access is the free, immediate, online availability of research articles combined with the
                        rights to use these articles fully in the digital environment.
                        <br>
                        <br>
                        Open Access is the needed modern update for the communication of research that fully utilizes
                        the Internet for what it was originally built to do—accelerate research. <br>
                        <br>
                        <br>
                        <a href="https://sparcopen.org/open-access/">SPARC on Open Access Journals</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<hr class="section-divider">

<!-- Ending Note -->
<section class="relative">
    <img class="absolute z-[-1] w-96 left-[85px] top-[-80px]" src="assets/img/background-shapes/end-note-bg.svg" alt="">
    <div class="mt-36 p-12 lg:grid grid-cols-2 inner--small items-center gap-12">
        <div>
            <h2><b>Note from<br> Open@RIT Team</b></h2>
            <hr class="subtitle-divider">
            <p>Open Work Definition is an open source document for everyone who wants to contribute to the open work
                community.
                <br><br>
                Please don't hesitate to contact us, send a pull request, and share your thoughts.
            </p>
            <button class="mt-8">Request Edit</button>
        </div>
        <img src="./assets/img/illustrations/two-people-talking.svg" alt="">
    </div>
</section>