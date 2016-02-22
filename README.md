# HSFMCV
Huguenot Society of the  Founders of Manakin in the Colony of Virginia

##Adding web pages
Simply copy the template to either the manakin directory or one of the branch directories. Add html content between the add content comments.

##Links and pictures
The site uses a base tag (in site/head.php). This causes relative links to start not in the directory of the page, but the base directory. The template has an example of adding a picture with a caption. Notice the image source is "Pictures/gate.jpg" instead of "../Pictures/gate.jpg" as might be expected if the page was in directory manakin. "/Pictures/gate.jpg" will also work.
