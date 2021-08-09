# horiseon-refactor
HTML CHANGES

    Firstly, the <title> was changed from <title>website</title> to <title>Horiseon</title>. 

    Then, majority of <divs> were replaced with more discriptive semantic tags. 
        Here is a list of the tags that replaced the <divs> tags
            * <div class="header"> to <header>
            * <div> to <nav> 
            * <div class="content"> to <main>
            * <div> to <article>
            * <div class="benefits"> to <aside>
            * <div class="footer"> to <footer>
    
    There was a broken link in the nav bar. The SEO link did not take the user to the SEO box. This required the 'id="search-engine-optimization"' to be added into the <article> tag of the SEO Section in the index.html. 

    All images were missing "alt:" attributes. These were added to all images. 

    Footer was changed from a <h2> to a <h3>. 

CSS CHANGES

    Redundancy was consolidated. 

    Elements were placed in more logical order. 

    IDs were removed and replaced with proper semantic tags. 

LINK TO WEBPAGE

    https://konnerhartman.github.io/horiseon-refactor/

SCREENSHOT
    ![plot](./assets/images/Horiseon-Refactor-Screenshot.png)
