# GOES_16_17_18_RGB

# This script uses the GOES-16 or GOES-17 ABI L1b Radiance product to create a georeferenced RGB True-Color image.
# This script will retrieve the ABI L1b-Rad files of interst from the Amazon Web Service (AWS) S3 Bucket.
# If the files of interest have previously been downloaded, skip cells 3-4 and proceed to Cell [7] to open files.

# SOURCES:
# Portions of this script have been modified and combined from other tutorials:
# 'GOES-16: True Color Recipe', and 'download_GOES_AWS.py' by Brian Blaylock
#           at https://unidata.github.io/python-gallery/examples/mapping_GOES16_TrueColor.html
#           and https://gist.github.com/blaylockbk/d60f4fce15a7f0475f975fc57da9104d#file-download_goes_aws-py
# "Using Python to Explore GOES-16 Data" at http://edc.occ-data.org/goes16/python/
