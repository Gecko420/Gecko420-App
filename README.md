# Gecko Download Manager (geckoDM) for Echo360
<div>
	<img src="/images/qtpi.png" width="100" >
</div>
Making Echo360 great again

<https://geckodm.github.io>

This project started because a 4 Monash kids were sick of downloading lectures individually and wanted to code instead of study during swotvac :laughing:we all failed :anguished:

[![](https://developer.chrome.com/webstore/images/ChromeWebStore_BadgeWBorder_v2_340x96.png)](https://chrome.google.com/webstore/detail/pgkfjobhhfckamidemkddfnnkknomobe/)


## Introduction

This [Chrome Extension](https://support.google.com/chrome_webstore/answer/2664769?hl=en) allows students to download all their lectures (_that they probably won't watch anyway_) from Echo360 online services with the click of a single button.

## Supported Institutions
To see supported institutions visit [https://github.com/GeckoDM/GeckoDownloadManager/wiki/Supported-Institutions](https://github.com/GeckoDM/GeckoDownloadManager/wiki/Supported-Institutions)

### Supporting:

<br/>
<div>
<a href="https://monash.edu">
	<img 
		src="https://www.monash.edu/__data/assets/git_bridge/0006/509343/deploy/mysource_files/monash-logo-mono.svg"
		height="60px" />
</a>
</div>
<br/>
<div>
<a href="https://www.unimelb.edu.au/">
	<img 
		src="https://brandhub.unimelb.edu.au/guidelines/logos/04_Logo_Vertical-Housed.jpg"
		height="120px" />
</a>
</div>
<br/>  
<div>
<a href="https://unsw.edu.au/">
	<img 
		src="https://www.unsw.edu.au/sites/default/files/UNSW_0.png"
		height="60px" />
</a>  
</div>
<br/>
<div>
<a href="https://www.ed.ac.uk/">
	<img 
		src="data:image/png;base64,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"
		height="60px" />
</a>
</div>
<br/>

## Usage

### 1. Go to the Echo download link provided by your institution.
<img src="/screenshots/screenshot-dl_link.png" >

### 2. Load the Echo page (via the link), click on the Gecko extension.
- Click on load Lectures.
- Select Lectures to download.
- Click on download.

<img src="/screenshots/screenshot-usecase.png" >

### 3. Downloading lectures.
<img src="/screenshots/screenshot-downloading.png" >

### 4. On Disk.
<img src="/screenshots/screenshot-datastore.png" >

## TODO
- [x] Figure out how to download stuff
- [x] ~~Handle download limits i.e. Can only download 6 files at a time.~~ I think Chrome handles this.
- [x] GUI
- [x] Specify download path (filesystem can only be used on Chrome apps, can have option to insert path via GUI?)
- [x] Name files downloaded
- [ ] Support incognito?
- [ ] Differentiate between recordings on the same day?
- [ ] Migrate to MDL (Material Design Lite)
- [ ] Fix download blocking (multiple downloads, slow internet)

## Known Issues
- Downloading many files in a short time span sometimes leads to Echo360 or Amazon S3 blocking downloads (sometimes it greys out lectures).

<img src="/screenshots/screenshot-blocked.png" >
