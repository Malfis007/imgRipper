## imgRipper
bash script to scrape sitemaps for urls and download images
- will scrape given file or try to download a sitemap to scrape

# usage
- pass either a sitemap file [-f] or a url to a sitemap [-u]

# todo
- currently only looks for \<image:loc\> tags within current sitemap; would like to add ability to scrape for sitemaps if the current sitemap has links to other sitemaps instead of image location tags
