<!--
@component
This is your page!
-->
<script>
  // Import all the news furniture components
  import ArticleHeader from '$lib/components/ArticleHeader.svelte';
  import ArticleBody from '$lib/components/ArticleBody.svelte';
  import Image from '$lib/components/Image.svelte';
  import RelatedLinks from '$lib/components/RelatedLinks.svelte';

  // Article metadata
  let headline = 'Diana Moreno Wins Election for the Mayor’s Assembly Seat';
  let byline = 'Benjy Sachs';
  let pubDate = '2026-02-05';

  // Related stories
  const relatedStories = [
    { headline: 'How America\'s top news organizations escape rigid publishing systems to design beautiful data-driven stories on deadline.', href: 'https://palewi.re/docs/coding-the-news/' },
    { headline: 'How to install, configure and use Visual Studio Code, GitHub and Copilot', href: 'https://palewi.re/docs/coding-the-news/scripts/week-1/' },
    { headline: "How to publish a website with Node.JS and GitHub Actions", href:"https://palewi.re/docs/coding-the-news/scripts/week-2/"},
  ];
</script>

<!-- This sets the page title in the browser tab -->
<svelte:head>
  <title>{headline} | NYCity News Service</title>
  <meta name="description" content="At the Craig Newmark Graduate School of Journalism at the City University of New York, change is in our DNA. That comes of being born in 2006, as the digital revolution was transforming our profession in ways none of us could have imagined." />
</svelte:head>

<!-- Your page content goes here -->
<div class="container">
  
  <!-- Article Header: Headline, byline, and publication date -->
  <ArticleHeader
    {headline}
    {byline}
    {pubDate}
  />

  <!-- Lead Image: Animated gif of students at the journalism school -->
  <Image
    src="/example-photo.gif"
    alt="The Craig Newmark Graduate School of Journalism is at 219 West 40th Street in Midtown Manhattan."
    caption="The Craig Newmark Graduate School of Journalism is at 219 West 40th Street in Midtown Manhattan."
    credit="Craig Newmark Graduate School of Journalism"
  />

  <!-- Article Body: The main story text with proper typography -->
  <ArticleBody>
    <p>
As Mayor Zohran Mamdani cruised to an improbable victory in the Democratic primary, three New York City Democratic Socialists of America stalwarts began to ask themselves the same question: Could I fill his shoes?

    </p>

    <p>
Mamdani’s vacated State Assembly seat required Gov. Kathy Hochul to schedule a special election for Feb. 3. Moreno won handily, receiving nearly three-quarters of the vote, beating out fellow DSA members Rana Abdelhamid and Mary Jobaida. Moreno will soon take her place in Albany, but the primary election for a full term will be held in June.

    </p>

    <p>
The election in Assembly District 36, which includes Long Island City and the so-called “People’s Republic of Astoria,” presented an opportunity for NYC-DSA to grow its political roster on the heels of its mayoral upset. Yet, as the ascendant leftist organization grapples with wielding executive power for the first time in New York City, the internecine race has also highlighted internal tensions. With few ideological differences to separate the candidates, NYC-DSA elevated a close ally of Mamdani — effectively deciding the race long before voters weighed in at the polls.

    </p>

    <p>
On Dec. 8, the group anointed Moreno, who recently served as Queens DSA co-chair and NYC-DSA’s communications coordinator. And then on Dec. 20, Mamdani himself endorsed Moreno — a huge boon in a district where he is incredibly popular.

    </p>

    <p>
Moreno said what set her apart in the race is her experience in NYC-DSA leadership and organized labor. She runs communications for the New York State Nurses Association, which is currently in the fourth week of its strike against several major hospital systems in the city. The former DSA leader also highlighted her advocacy against Immigration and Customs Enforcement, an issue that she says is deeply personal, having immigrated from Ecuador as a child. Moreno was arrested at an anti-ICE protest at 26 Federal Plaza in September alongside several elected officials.

    </p>

    <p>
She positioned herself as an energized leader ready to help Mamdani implement his campaign promises.

    </p>

    <p>
“He’s going to need unwavering allies in Albany,” Moreno said.

    </p>

    <p>
She stressed the need for the socialist group to unify around its endorsed candidate.

    </p>

    <p>
“I committed myself to suspend my campaign if I didn’t get the New York City DSA endorsement,” Moreno said. “To me, that is sort of the litmus test for who really is a DSA candidate.”

    </p>
    <p> However, not every DSA politician lined up behind Moreno.

</p>
<p> Rep. Rashida Tlaib endorsed Abdelhamid, the founder of Malikah, a nonprofit that offers self-defense training to New Yorkers, especially Middle Eastern and North African women.

</p>
<p> Tlaib headlined a star-studded fundraiser for Abdelhamid on Dec. 14 at Ayat Astoria, a Palestinian restaurant, joined by former Comptroller Brad Lander and Councilmember Julie Won.

</p>
<p> “I have a preexisting relationship with Rana,” Tlaib told NYCity News Service when asked why she supported Abdelhamid over Moreno, NYC-DSA’s endorsed candidate. “I feel very much like she’s been my mentee … She’s a friend and a sister and I’m going to support her.”

</p>
<p> Lander also spoke at the event about his personal relationship with Abdelhamid, who is Egyptian-American and Muslim. He highlighted the importance of building solidarity between Jewish and Muslim New Yorkers.

</p>
<p> “This morning when, after this horrific killing in Sydney,” Lander said, referencing the shooting targeting Jews at Bondi Beach, “one of the first texts I got was from my Muslim sister, from Rana Abdelhamid.”

</p>
<p> Abdelhamid, who was born and raised in Astoria, emphasized her deep roots and longtime organizing work in the district.

</p>
<p> “I’ve been on the front lines, working on food security, supporting asylum seekers, organizing for housing security,” Abdelhamid said. “People have seen my work firsthand. They’ve worked alongside me. They’ve marched with me. I think that is the kind of leadership people want.”

</p>
<p> Rounding out the field was another longtime organizer. Jobaida, who moved to New York from Bangladesh in 2001, is a community activist who has worked in education, media, and local politics.

</p>
<p> Her campaign focused on affordability and on building housing that working-class people can afford. She said that witnessing gentrification and displacement in Long Island City has demonstrated the shortcomings of the city’s housing policy. She criticized the Long Island City neighborhood plan that passed the City Council on Nov. 12 for not including enough affordable housing.

</p>
<p> Jobaida ran for State Assembly in 2020 in district 37, before redrawn boundaries moved her into her current district. She finished second in the Democratic primary, losing by about 10%.

</p>
<p> “No big organization endorsed me,” Jobaida said of her 2020 campaign. “Because I had to run my campaign almost alone, I got extremely experienced and savvy about campaigning.”

</p>
<p> She believed her electoral experience and enthusiastic support from the Bangladeshi community would help her win the race. Still, losing out on NYC-DSA’s this time around stung.

</p>
<p> “I felt heartbroken,” Jobaida said. “This is my family.”

</p>
<p> Jobaida vowed to continue campaigning despite missing out on the organization’s backing.

</p>
<p> “I think that I will make DSA proud in another way,” Jobaida said. “And I’m still socialist. You cannot change me. You may disown me, but I’m still a socialist.”

</p>
  </ArticleBody>

  <!-- Related Stories: Links to other articles -->
  <RelatedLinks
    title="Related Stories"
    links={relatedStories}
  />

</div>

<style>
  /* Styles here only apply to this page */
  .container {
    padding: var(--spacing-lg) var(--spacing-md);
  }
</style>