Partners: Ali Farahbakhsh, Jay Gao

1. I would run them in a Github action, because if we were to only run them locally, just because it works on my machine does not indicate that it may work on others. Also, the choice of running tests AFTER development is not ideal, as some parts of our code can crash, ruining the entire product after everything is done. So having tests on github actions is the best choice as it can test our code after each update or change pushed to Github, avoiding errors and issues interfering with other code.

2. No.

3. Navigation mode navigates to the given url then runs a performance audit. On the other hand snapshot takes a snapshot of the currently loaded state of the app and audits that. Navigation analyzes how the app performs on initial load where as snapshot analyzes how the current state of the app is. Snapshot is useful for analyzing the page after certain interactions while navigation is good for analyzing the user exprience when they initially come into the website.

4. Based on the lighthouse results, the page doesn't have a `<meta name="viewport">` tag. Also, images were larger than their displayed size and the `<html>` element doesn't have a `[lang]` attribute. These are some improvements that could be done to the shop website to improve the site's score and improve accessiblity and SEO/Performance.  The attribute and the tag are pretty easy to add and the image issue can be addressed by serving images that are not bigger than what is required by our website.