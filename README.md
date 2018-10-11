# mach5.org

files for mach5.org

update:

(obv need key)

aws s3 sync --sse AES256 --storage-class STANDARD --exclude .DS_Store --exclude README.md --exclude LICENSE --exclude '.git/*' --delete --dryrun . s3://mach5.org/
