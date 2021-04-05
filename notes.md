## errors in readme, file names, within files

readme for code, clean_scraped_data.py should say data/raw/scraped_posts.txt

name of code file incorrect: NBER-post-history-ID (by part).R, remove -round2
within NBER-post-history-ID (by part).R: nber-ejr-author-info.csv, remove -ejr

in merge-sources.R, fix file path for JMC
merge-sources.R, warning message: full_sample2019.csv loses info

clean_raw_text.R, also warning message: EJR0_raw_text_cleaned.csv probably loses info??
clean_raw_text.R: str_only_Nov2017.csv  what is this file???

move codebook_datasets.xlsx and codebook_full_sample2019_dta.log into results_static
static .do file creates codebook_dta.log

-  the two above log files are supposed to be the same, but the name in the .do file has changed

# thoughts

what to do if the diagram tree is more like a conic? all the data funnels into one final analytic dataset, and then a bunch of figures/tables come out of that separately
it's more like a diagram tree+root system
