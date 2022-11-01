# bxv.gg
All files associated with bxv.gg

## What happened?
Today our cloudflare account got compromised and our websites got deleted. That gave us some time to think about whether or not we want to continue bxv. In the last couple of months, neither me, nor voltic really cared about bxv. I did some occasional updates to address some issues (like typos, lol) up to a month ago and then also stopped caring. The truth is, we got bored. We made bxv to see wether or not we could block ddos attacks without disturbing the user. Safe to say, whoever was here while bxv was alive, knows that's exactly what we accomplished. The source of our challenge itself became a cluster-fuck and incredible annoying to maintain. That's why we decided to "leak" it now. You can find the unobfuscated version over at https://bxv.gg/cookie. We will not tell you how to use it, however our internal ReadMe can be found over at https://bxv.gg/readme.md. This is so at least it will stop at least some skids from just copy pasting our challenge. If you do use our challenge or use parts of it, that were not open-source before (there are some parts of our challenge that are public knowlege, like checking for webdriver etc) it would be apprechiated if you give at least some credit to voltic, baloo or alexa, a person that operated behind the scenes. Our unobfuscated captcha can be found at https://bxv.gg/captcha and should be a lot easier to use.

## Huge thanks to:
**@V0ltic** for getting me started with basic bot detection and testing,
**@KillerCatLion** for helping me create this awesome website, who's code is now unobfuscated and the console can be found at https://bxv.gg/assets/js/console.js
and **all of you**, that helped me debug and patch your attacks (`@udbnt`, `@That1G`, `@tcpurg`, just to name a few). I couldn't have done it without you.
Anyone that helped me in the past can dm me `@ddosmitigation` on telegram and i will help them how to use the bxv challenge."

# Internal ReadMe

# Browser Identifiers:

### Trusted (most people dont spoof these):
- **Windows** = qrup
- **Linux** = afjo
- **Mac** = yvmp
- **IPhone** = ikhg
- **IPad** = fiha
- **Mobile (General)** = tdim

### Not Trusted (most people spoof these):
- **Windows** = wayx
- **Mac** = esxc
- **Linux1** = rdcv
- **Linux2** = tfvb

### Depricated OS Identifier:
- **Windows** = ocshjk
- **Mac** = ocsbnz
- **Linux** = ocsgbh

# Detection Cookies:

- **dam** -> Spoofed Useragent
- **sic** -> Missmatching Monitor (puppeteer)
- **ans** -> Webdriver exists
- **aan** -> Advanced Webdriver exists
- **tds** -> WebGL Vendor
- **bns** -> WebGL Renderer
- **fso** -> ScreenHeight = OuterHeight
- **fst** -> OuterHeight = 600, OuterWidth = 800
- **ebv** -> Vendor does not exist ("")
- **vhe** -> All Screen Dimensions The Same
- **ccfg** -> Browser Emulation (T1G)
- **lass** -> Lied Monitor Size
- **abem** -> Missing Language
- **tcrt** -> Connection TTR
- **tmdns** -> MimeTyes
- **tppt** -> Plugin Check
- **mbcb** -> Error Stack Check
- **ngot** -> Overwrite Check
- **ovft** -> Overflow Check
- **chcim** -> Broken Image Test
- **wglla** -> WebGL Vendor & Renderer less agressive
- **jbmb** -> Undefined Battery
- **jbmc** -> Undefined Memory
- **jbmm** -> Undefined Media
- **wppb** -> Puppeteer PDF Proterties
- **__pftbn_** -> Broken PDF
- **__pjbe_** -> Broken PDF Support Reporting
- **ifsfb** -> Iframe Detection
- **jbmm** -> Reports Having No Devices
- **fsbel** -> Reports Being Offline
- **epnd** -> Empty UserAgentData Platform
- **rcem** -> Connection RTT Is 0
- **ebnd** -> UserAgentData Brands Is Empty ([])
- **bhbc** -> Bluetooth Is Undefined
- **tcins** -> Website Is "http://"
- **iotd** -> Overwrite Check New
- **iofd** -> Overflow Check New
- **cjco** -> Notification Check
- **cjct** -> Viewport Check
- **cjch** -> Render Check

- **tyya** -> Manipulation Protected Cookie Verifier

# Fingerprint:

- **bfpw** -> WebGL Fingerprint
- **bcfpc** -> Consistant Canvas Fingerprint
- **bnfpc** -> Non-Consistant Canvas Fingerprint