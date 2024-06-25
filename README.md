<h1 class="entry-title">How to sign/install (sideload) iPA (iPhone App) files in the easiest way possible without any expiry period for free?</h1>
<div class="entry-content">
					
<p>Relax, this is a tutorial and if you’re a seasoned torrentor than this should be fairly quick to learn even without the explanation but for anybody else this should be the simplest tutorial for you regardless as everything has been compressed here itself rather than sending you to multiple sources.</p>



<h2 class="wp-block-heading">Sideloading Guide</h2>



<ol class="wp-block-list">
<li><strong>DNS</strong><br><a href="https://github.com/ESign-khoindvn/ESign-Khoindvn.github.io/raw/main/Tool/khoindvn.mobileconfig">https://github.com/ESign-khoindvn/ESign-Khoindvn.github.io/raw/main/Tool/khoindvn.mobileconfig</a></li>



<li><strong>Esign</strong><br><a href="https://api.khoindvn.eu.org/qicjtt">https://khoindvn.bio.link</a></li>



<li><strong>Certs</strong><br><a href="https://github.com/dns-khoindvn/dns-khoindvn/raw/main/dns/ESign-cert.zip">https://github.com/dns-khoindvn/dns-khoindvn/raw/main/dns/ESign-cert.zip</a></li>



<li><strong>Repo</strong><br><a href="https://raw.githubusercontent.com/swaggyP36000/TrollStore-IPAs/main/apps_esign.json">https://raw.githubusercontent.com/swaggyP36000/TrollStore-IPAs/main/apps_esign.json</a></li>
</ol>



<h1 class="wp-block-heading">Start DNS</h1>



<p><strong>About:</strong> This is a DNS Profile from <strong>Khơindvn</strong> (<a href="https://github.com/ESign-khoindvn/dns-khoindvn">GitHub</a>) via the courtesy of a YouTuber named ‘Pork the Jork’ meant to filter Apple Servers which verifies the bundle ID of an app that’s going to be signed before getting installed since on iOS or iPadOS, apps aren’t signed locally unlike on a PC or Mac post iOS 13. So, if you’re blacklisted then this should get you back in the line as well.</p>



<h2 class="wp-block-heading">Step 1:</h2>



<ul class="wp-block-list">
<li>Make sure <strong>Safari</strong> is your default browser or is used before tapping on the <a href="https://github.com/ESign-khoindvn/ESign-Khoindvn.github.io/raw/main/Tool/khoindvn.mobileconfig">link</a>.</li>



<li>Go to <strong>Settings → General → VPN, DNS, Device Management</strong></li>



<li>Install the profile and let it work.</li>
</ul>



<figure class="wp-block-image size-large"><img src="https://i.imgur.com/ovPqORh.png" alt=""><figcaption class="wp-element-caption">So, you can see based on user feedback I’ve solely resorted to Khơindvn’s solution instead of copycats (like Khomod) forking from his original GitHub repository. His website might be in non-english (in a clever way to avoid internet scans that issue notices from US) but his repo has everything authored in clean english as an open project for all to inspect and replicate.</figcaption></figure>



<h1 class="wp-block-heading">Install Esign</h1>



<p><strong>About:</strong> Esign is a signing app that can download, unzip, package, import, sign and install iPA files to become apps in addition to accessing public repos directly.</p>



<h2 class="wp-block-heading">Step 2:</h2>



<ol class="wp-block-list">
<li>Tap on the <a href="https://api.khoindvn.eu.org/qicjtt">link</a> to install Esign (Sunshine Insurance Group) directly after following the steps above of using the custom DNS filters or grab a different one from <a href="https://khoindvn.bio.link">here</a>.</li>



<li>Go to <strong>Settings → General → VPN, DNS, Device Management → Enterprise App</strong></li>



<li>Tap on the Certificate Name and there should be a Trust button.</li>



<li>Now open the Esign app and under the ‘Download’ Tab in the bottom navigation bar, find the ellipses ••• on the top then ‘Settings’ to enable both ‘Auto Import’ &amp; ‘Auto Delete’</li>
</ol>



<figure data-carousel-extra="{&quot;blog_id&quot;:69217765,&quot;permalink&quot;:&quot;https:\/\/avieshek.wordpress.com\/2024\/06\/11\/how-to-sign-install-sideload-ipa-iphone-app-files-in-the-easiest-way-possible-without-any-expiry-period-for-free\/&quot;}" class="wp-block-gallery alignfull has-nested-images columns-default is-cropped wp-block-gallery-1 is-layout-flex wp-block-gallery-is-layout-flex">
<figure class="wp-block-image size-large"><img src="https://i.imgur.com/GrFNPW9.png" alt=""></figure>
<figcaption class="blocks-gallery-caption wp-element-caption">Download Setting for Esign</figcaption></figure>



<h1 class="wp-block-heading">Get Certs</h1>



<p><strong>About:</strong> Cert is simply short for certificate where we’ll use the expired ones instead of the latest one… presumably HDFC Life Insurance (Indian) or older like Sunshine Insurance Group (Chinese) but you’ll be downloaded with all of them.</p>



<h2 class="wp-block-heading">Step 3:</h2>



<ol class="wp-block-list">
<li>Tap on the <a href="https://github.com/dns-khoindvn/dns-khoindvn/raw/main/dns/ESign-cert.zip">link</a> here or copy from above then go to your: &nbsp;
<ul class="wp-block-list">
<li>Esign → Download → ••• → URL › Paste</li>
</ul>
</li>



<li>A zip file should be in your ‘File’ section, there’s inbuilt uncompressor so you just need to tap after which there will be an extracted folder by the same name.</li>



<li>There should be a list of certificates, we used the Sunshine cert to install Esign so we will only import the “Sunshine Insurance Group Certificate”.
<ul class="wp-block-list">
<li>If you used a different cert for Esign installation (say HDFC) then use that one.</li>



<li>After successful import, you can delete both the folder and the zip file.</li>
</ul>
</li>



<li>Now go to the main ‘Settings’ in the app (bottom bar) for “Sign Default Config” where you’ll enable “Install after signed” and get out.</li>
</ol>



<figure class="wp-block-image size-large"><img src="https://i.imgur.com/z6gVaCZ.png" alt=""></figure>



<h1 class="wp-block-heading">Load Repo</h1>



<p><strong>About:</strong> Repo stands for repository which should allow to act like an App Library of sort, the one I have mentioned here for instance is TrollStore iPA Library from GitHub.</p>



<h2 class="wp-block-heading">Step 4:</h2>



<ol class="wp-block-list">
<li>Tap on the <a href="https://fwuf.in/#/esign://addsource?url=https://raw.githubusercontent.com/swaggyP36000/TrollStore-IPAs/main/apps_esign.json">link</a> or manually copy from above to Esign → App Source (Top Left) → + &nbsp;</li>



<li>Now see yourself being able to search and download natively.</li>
</ol>



<figure class="wp-block-image size-large"><img src="https://i.imgur.com/yntP97H.jpeg" alt=""></figure>



<h1 class="wp-block-heading">Install Part</h1>



<p><strong>About:</strong> If you’ve been following attentively up to here then you’d notice you’re yet to install an app and that’s because unlike the AppStore itself the search function only downloads the app as you’d need to sign it first.</p>



<h2 class="wp-block-heading">Step 5:</h2>



<ul class="wp-block-list">
<li>You’d notice on the initiation of this final process is the <strong>‘Signature’</strong> button above the ‘Install’ one. This is what’s more important and would be used more unless you’re duplicating (more on that later) an already signed app like WhatsApp.</li>
</ul>



<figure class="wp-block-image size-large"><img src="https://i.imgur.com/31awtJi.jpeg" alt=""></figure>



<h1 class="wp-block-heading">How to Duplicate Apps with Esign?</h1>



<p><strong>About:</strong> There are instances when you’d like to have duplicate apps because you want to keep the original, have the flexibility of multiple messaging accounts or want to maintain two separate use cases. Usually, I use this Shortcut called <a href="https://www.reddit.com/r/shortcuts/comments/17d6ef8/">Signed Installer</a> but Esign can allow duplicating apps too.</p>



<h2 class="wp-block-heading">Steps:</h2>



<ol class="wp-block-list">
<li>Modify the App name to your custom name (for example: YouTube Red) or add + symbol after the original app name, just make sure to change the original name used.</li>



<li>Add “ .1 “ to the <strong>bundle identifier</strong>, if example bundle identifier is “com.google.ios.youtube” then change it to “com.google.ios.youtube.1”</li>
</ol>



<h1 class="wp-block-heading">Final Notes</h1>



<p>There are a couple of things that you might want to remember which is just basic common sense:</p>



<ul class="wp-block-list">
<li>If one certificate doesn’t work for you, then simply try another… in the end, it works out for everybody but older the better.</li>



<li>There can be instances when you’re still failing to initiate, the Esign app itself is pretty much not that polished because it has only one function to perform. Simply uninstall the app, cert or even DNS involved in this process and start fresh with a different certificate but this is an issue only for virgin sideloaders.</li>



<li>If you’re only stuck somewhere in the middle, remind yourself with the following basic questions:
<ul class="wp-block-list">
<li>Did you finish reading?</li>



<li>Did you try with another attempt?</li>



<li>Did you explore everything laid out to you?</li>
</ul>
</li>
</ul>
