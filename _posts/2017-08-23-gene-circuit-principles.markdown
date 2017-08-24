---
layout: post
comments: true
title:  "Circuitry Perspective of The Genetic Program"
date:   2017-08-23 14:56:05 -0700
categories: biology update
---
Amongst the concepts imagined to be integral part of a
personalized/precision medicine ecosystem is genetic circuits. As in
electrical circuits they are designed by coordinating various parts
(e.g. genes, promoters, binding sites) each with a known function such
that together a the desired behavior. Figure bellow (copied from paper:
*Principles of genetic circuit design, 2014, Brophy, Voigt*) illustrates
a conceptual genetic circuit hosted by a therapeutic bacterium colonized
in the interior of human gastrointestinal tract. The circuit, not only
produces drug upon sensing the disease biomarker, but also avoids drug
overdose.

<img src="/assets/posts/2017-08-23-gene-circuit-principles-fig.jpg" />

Figure Conceptual genetic circuit, copied [from Nature
journal](https://www.nature.com/articles/nmeth.2926).

The schematic on the bottom of the figure are to illustrate some
necessary to make such circuit function as expected. This figure seems
very idealistic given the status of the filed. As authors describe the
state of, genetic circuitry parts are not so plug and play. Their
function is often very context dependent. Much knowledge, experience,
mathematical modeling and experimental debugging is necessary to build
such circuitries successfully.

It is mind boggling to imagine the details necessary for a genetic
program involving of ~4000 genes as in Escherichia to function and
thrive. It seems to me, the big break-through in the “hardware” of
biology is necessary before useful “software” can be written. Perhaps
contribution of us (computer scientist), would be in developing (I)
simple, extensible, debug-able and predictive models and tools, (II)
reverse engineering methods and (III) more useful perspectives (other
than circuits), for such intricate systems.

{% if page.comments %}  
<div id="disqus_thread"></div>
<script>

/**
*  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
*  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables*/

var disqus_config = function () {
this.page.url = 'https://ameenetemady.github.io/biology/update/2017/08/23/gene-circuit-principles.html';  // Replace PAGE_URL with your page's canonical URL variable
this.page.identifier = 'gene-circuit-principles'; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
};

(function() { // DON'T EDIT BELOW THIS LINE
var d = document, s = d.createElement('script');
s.src = 'https://ameenetemady-github-io.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
{% endif %}
