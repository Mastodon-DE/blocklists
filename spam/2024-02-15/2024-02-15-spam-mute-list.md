# Current Mute List - 4.0.0: The UNmute List
Regarding the Fediverse Spam Attacks that started on the 15th of February (ongoing)

**Last Updated:** 2024-04-22 | 16:47 UTC <br/>
**By:** Erik Uden (*mastodon.de, troet.cafe, muenchen.social*)

## Please Read:
**Final Update - 2024.04.22**
This specific spam wave is now over. I am thankful to everyone involved and urge every Fedi-Admin to unmute every instance that is no longer on this list! The only instances still on this list are:
- **A)** Those instances where spam is still stored, meaning the admins never logged in to remove it and the spam simply stopped because the spammers got arrested. 
- **B)** The instances that went offline and hence could return with spam if they ever go online again. 

If your instance is on this list it means you haven't responded to this spam problem for over two months. The admins of these instances have abandoned them, hence they can be used for the next spam attack just like they were used for this one! Hey, this list is *generous*, some instances have been removed from here because their admins were contacted through Instagram or other third-party platforms and notified of what is going on over here on the part of the internet they *should* be taking responsibility for. If people of the Fediverse have to go through these lengths to tell you what is going on with your server, well... heh! I can't really complain, [I've been in the same spot and have committed the same cardinal sin](https://mastodon.de/@ErikUden/111483146986978449). **I am willing to forgive every admin, even if it has come this far!** Just reach out and I'll get your instance off this list even if this was my "final" update ;)!

Lists like these will likely never need to be shared again! Remember this moment, as it is an integral part of Fediverse history ***you*** were a part of! IFTAS is already working on shared blocklists, meaning you can subscribe to a list where instances automatically get added or removed, making this entire thing obsolete in the future! Also, Mastodon has created some standards for newer versions where an instance automatically turns off sign-ups if an Admin account doesn't login for some time, which would've stopped 99% of the spam instances after the first day. Deleting posts or banning users by keywords will also be added, similar to the script that fixed spam entirely which many big instances got from the Mastodon team. Also notification filters have been added so new accounts can't even be used for spam. So much has changed...

This problem we faced has, as of now, been crushed into the ground with no sight of recovery. Tools like this list will likely never be needed again to fix any spam problem, which is exciting! 

I cannot thank the people that helped here enough, truly! Additionally, everyone that shared this list and talked about it publicly just made my day, from [Brodie Robertson](https://youtu.be/_KCwq9e-H5M?feature=shared&t=654) to [TechCrunch](https://techcrunch.com/2024/02/20/spam-attack-on-twitter-x-rival-mastodon-highlights-fediverse-vulnerabilities/) it was surprising to see how many people this list spread to and possibly helped!

Thank you, Fediverse Community!
*Doing any work for you **always** feels rewarding!* <3

Yours in solidarity,
Erik Uden


**How To Ban Spam Accounts Locally (and Sustainably)** <br/>
https://mastodon.de/@ErikUden/111940301222380638

**Why did this Spam happen?** <br/>
https://blog.fyralabs.com/cyberbullying-gone-global-regarding-the-fediverse-spam-and-operation-beleaguer/ </br>
Apparently the people behind this spam have been arrested in Japan. 

**Also Note** <br/>
Importing this list will not affect the status of instances you have already moderated! While all this list does is mute, if any of the instances on this list are already suspended by you, that entry will not be changed (*on Mastodon*). 

## Please Donate!
**I've worked on this list for the good part of many days!** I am a university student, local politician, I run and organize food drives once a month, I run a holocaust remembrance exhibition, and *on the side* do these Mastodon instances (*troet.cafe, mastodon.de, muenchen.social*), which is why I would highly appreciate it for you to **[donate here](https://mastodon.de/@MastodonDE/110808633497349326)** so I can somehow justify spending so much time on this! Heh. 

## Your Instance Should not be here?
If you're the admin of an instance listed here and you've taken care of the spam issue and do not think what we wrote about your instance here is accurate, or you do not know why you're on this list at all, please message me on Matrix (*[ErikUden:matrix.org](https://matrix.to/#/@erikuden:matrix.org)*) or E-Mail (*[fedi-spam@uden.ai](mailto:fedi-spam@uden.ai)*). I sincerely apologize for putting you on here and causing trouble!

### Special thanks to:
- [@graphite@eepy.zone](https://shonk.phite.ro/@graphite) for making me aware of this issue (*2024-02-15 | 18:42 GMT+1*)!
- [@martinmuc@muenchen.social](https://muenchen.social/@martinmuc) for making me aware of this issue (*2024-02-16 | 08:32 GMT+1*)!
- [@lety@doesstuff.social](https://doesstuff.social/@lety) for checking the list long after the spam was over!
- [@Sleagle@mastodon.de](https://mastodon.de/@Sleagle) for helping me create this spam list!
- [@FanCityKnits@troet.cafe](https://troet.cafe/@FanCityKnits) & [@catflyhigh@troet.cafe](https://troet.cafe/@catflyhigh) for reporting hundreds of spammers to troet.cafe!

And last but not least I heavily thank [@southernwolf@furry.engineer](https://furry.engineer/@southernwolf), [@vavency@kitsunes.gay](https://kitsunes.gay/@vavency), [@otterX@mindly.social](https://mindly.social/@otterX), and [@admin@hear-me.social](https://hear-me.social/@admin) for giving me their updated spam list!


## The Mute List

**Download and import the updated list of instances observed to have spam to mute:** [Download Here](https://github.com/Mastodon-DE/blocklists/blob/main/spam/2024-02-15/2024-02-15-spam-domain_mutes-erik-uden.csv). <br/>
*This includes all instances with a threat level of 1-5*. <br/>
This list is about 100% of what instances we currently have reported as of this update. Note that while all instances can be imported with one click, in order to remove them once the spam is over you'll need to remove them all individually. <br/>

You can simply import that list by going to `https://yourinstance.tld/admin/export_domain_blocks/new` just replace `yourinstance.tld` with the domain of the instance you are an admin of. 

Alternatively press on `Settings => Moderation => Federation => Import` to import this list. 
Note that it only makes sense to import this list and mute the spam instances if you've blocked spam locally and sustainably as described [here](https://mastodon.de/@ErikUden/111940301222380638). 

### Explanation/Glossary

**Most recent spam wave: March 30th**

As of writing this update, the most recent spam wave tied to the original exploit from February 15th seems to have been on March 29th.

**Threat level: the higher the worse of a threat the instance is**

- *Threat Level 0:* These instances were on the list, but admins have since taken action and removed spam sustainably. They are listed under "Refederate with // Spam stopped".
- *Threat Level 1:* These instances have been observed to have had spam, but they are currently down, and we cannot say for sure whether the admins have sustainably stopped the spam or if it will continue once the instance turns on again.
- *Threat Level 2:* These instances no longer send out spam posts, but old ones are still stored on the instance. This could be because the admins took action preventing spammers from creating accounts and hence removing spam sustainably or because the spammers simply decided to stop targeting their instance. If the latter was the case, spam could start at any moment if the spammers decide to do so.
- *Threat Level 3:* These instances are observed to either actively send out spam or have done so during the most recent spam wave.
- *Threat Level 4:* These instances were observed to have spam, and they were re-classified to be safe, but then the spam began again, meaning either a new wave/kind of spam has infected this instance or the admins did not take measures to sustainably prevent spam. 
- *Threat Level 5:* These instances are observed to either actively send out spam or have done so during the most recent spam wave. Additionally, they have stored spam for over thirty (30) days, and the admins have done nothing against it.

### Mute // Spam Ongoing

The admins of the below instances have, to the best of my knowledge, not mitigated the spam issue, muting them would be helpful to stop spam reaching your users. 

#### Threat Level 5: Had Spam for a long time
- `9kb.me` (*[Most recently Mar 26](https://9kb.me/@bhkewcmcak/112160637946679465), [dating back until at least Feb 24](https://9kb.me/@bhkewcmcak/111986409328406660)*)
- `bigballchunkyverse.online`(*[Most recently Mar 30](https://nasface.cz/@1yltv7ncvx/112183056969215526), [dating back until at least Feb 24](https://nasface.cz/@nkwycfznft/111986408091957912)*)
- `discourse.helenprejean.org` (*[Most recently Mar 30](https://discourse.helenprejean.org/@qzuq2ncrdi/112183058091942742), [dating back until at least Feb 24](https://discourse.helenprejean.org/@qzuq2ncrdi/111986410587252489)*)
- `i.transmit.love` (*[Most recently Mar 30](https://i.transmit.love/@h7gmkr0sqn), [dating back until at least Feb 24](https://i.transmit.love/@rjpykwkhdc/111986409811714035)*)
- `nasface.cz` (*[Most recently Mar 30](https://nasface.cz/@1yltv7ncvx/112183056969215526), [dating back until at least Feb 24](https://nasface.cz/@ksh1oimypq/111986410274784798)*)
- `niederbayern.social` (*[Most recently Mar 30](https://niederbayern.social/@0shlgh4erw/112183058083021147). [dating back until at least Feb 24](https://niederbayern.social/@9ztsupzynz/111986410388307284)*)
- `lllsecurity.com` (*[Most recently Mar 30](https://lllsecurity.com/@vl8eutxiwb), [previously cleared around Mar 8](https://mastodon.social/@gunchleoc@ailbhean.co-shaoghal.net/112061352971583639)*)

#### Threat Level 4: Were previously thought to be safe but still spam
- N/A


#### Threat Level 3: Currently sending out spam posts
- N/A

#### Threat Level 2: Store Spam but no longer send out Spam
- `freesocial.co` (*[Spam paused on Feb 20](https://freesocial.co/@kwmk7mbqhx/111962288796215750)*)
- `rtypedbs.hostdon.ne.jp` (*[Spam paused on Feb 20](https://rtypedbs.hostdon.ne.jp/@g9fbx3zkjm/111962200727337840)*)
- `sensitive.hostdon.ne.jp` (*[Spam paused on Feb 19](https://sensitive.hostdon.ne.jp/@ghykv7y6g1/111960427058585032)*)
- `thoughtful.social` (*[Spam paused on Feb 20](https://thoughtful.social/@mzjzvifkwx/111961600977629070)*)

#### Threat Level 1: Offline / Can't load home timeline
- `archaeology.social` (*Offline*)
- `bondsdogs.com` (*Offline*)
- `cherryberry.pink` (*Offline*)
- `cryptodon.lol` (*Can't load timelines*)
- `cunnyborea.top` (*Offline*)
- `cuyes.mooo.com` (*Can't load timelines*)
- `devsrv.farhan.codes` (*Offline*)
- `digitaldata.social` (*Offline*)
- `dtris.moe` (*Offline*)
- `edusocial.it` (*Offline*)
- `fusionpros.social` (*Offline*)
- `game-tecx.de` (*Offline*)
- `games.retrotalk.live` (*Offline*)
- `hdty.in` (*Offline*)
- `kernkraft.social` (*Offline*)
- `kokuusa.club` (*Offline*)
- `kotodama.space` (*Offline*)
- `m.techsocial.site` (*Offline*)
- `mastadon.astuto.cc` (*Offline*)
- `mastodon-omikron-alpha.net` (*Offline*)
- `mastodon.conquestuniverse.com` (*Can't load timelines*)
- `mastodon.io.seg.br` (*Offline*)
- `mastodon.thedirtydis.co` (*Offline*)
- `mentalhealthmasto.com` (*Offline*)
- `neuroscience-mastodon.com` (*Offline*)
- `onion.social` (*Offline*)
- `onlybsds.com` (*Offline*)
- `scfzfilm.org` (*Offline*)
- `smooth.guru` (*Can't load timelines*)
- `social.cutefunny.net` (*Offline*)
- `tambayan.us` (*Offline*)
- `tech.retrotalk.live` (*Offline*)
- `tut.andreer.no` (*Offline*)
- `waterlily.tokyo` (*Offline*)


### Refederate with or unmute // Spam stopped

**Threat Level 0: SAFE! Refederate with or unmute these instances!**

These instances had spam but since have taken action in order to stop it. If any other lists tell you to defederate from these instances, they're probably outdated. 

- ~~0x3c.pl~~ (*[Fixed](https://0x3c.pl/@centrala/111951816200466414)*)
- ~~430022.xyz~~ (*[Fixed](https://drive.proton.me/urls/ZMYAJPDF54#II2wUrd7FITp)*)
- ~~academia.pub~~ (*Fixed*)
- ~~adforward.org~~ (*Fixed*)
- ~~aether.run~~ (*Fixed*)
- ~~airwaves.social~~ (*Fixed*)
- ~~america.social~~ (*Fixed*)
- ~~amigosblasterradio.masto.host~~ (*Fixed*)
- ~~andrew.xyz~~ (*Fixed*)
- ~~asturias.red~~ (*[Fixed](https://old.mermaid.town/@futzle/111950327071885006)*)
- ~~autistics.life~~ (*Fixed*)
- ~~azemet.space~~ (*Fixed*)
- ~~basstdn.jp~~ (*Fixed*)
- ~~batchats.net~~ (*Fixed*)
- ~~besties.com~~ (*Fixed*)
- ~~beyond.forum~~ (*Fixed*)
- ~~bibletalk.social~~ (*[Fixed](https://drive.proton.me/urls/ZMYAJPDF54#II2wUrd7FITp)*)
- ~~boop.network~~ (*[Fixed](https://drive.proton.me/urls/ZMYAJPDF54#II2wUrd7FITp)*)
- ~~castilla.social~~ (*Fixed*)
- ~~closednetwork.social~~ (*Fixed*)
- ~~cmm.fyi~~ (*Fixed*)
- ~~comunitate.ascorcluj.com~~ (*Fixed*)
- ~~crosstalk.tech~~ (*Fixed*)
- ~~cryptodon.chat~~ (*Fixed*)
- ~~cybersecurity.masto.host~~ (*Fixed*)
- ~~dabzyum.masto.host~~ (*[Fixed](https://drive.proton.me/urls/ZMYAJPDF54#II2wUrd7FITp)*)
- ~~daotodon.me~~ (*[Fixed](https://drive.proton.me/urls/ZMYAJPDF54#II2wUrd7FITp)*)
- ~~daytongang.social~~ (*Fixed*)
- ~~det.social~~ (*[Fixed](https://det.social/@stefan/111940822126104456)*)
- ~~detmi.social~~ (*Fixed*)
- ~~don.neet.co.jp~~ (*Fixed*)
- ~~dreamersreality.dev~~ (*Fixed*)
- ~~drobny.blog~~ (*Fixed*)
- ~~e.fo~~ (*Fixed*)
- ~~educhat.social~~ (*Fixed*)
- ~~electroverse.tech~~ (*Fixed*)
- ~~ellis.social~~ (*[Fixed](https://drive.proton.me/urls/ZMYAJPDF54#II2wUrd7FITp)*)
- ~~esglife.social~~ (*Fixed*)
- ~~estrogen.cat~~ (*[Fixed](https://drive.proton.me/urls/ZMYAJPDF54#II2wUrd7FITp)*)
- ~~exmormon.social~~ (*Fixed*)
- ~~fanfare.horse~~ (*Fixed*)
- ~~fckmsk.social~~ (*Fixed*)
- ~~federated.place~~ (*Fixed*)
- ~~fedibird.com~~ (*[Fixed](https://fedibird.com/@noellabo/111969334550914142)*)
- ~~fediverse.science~~ (*Fixed*)
- ~~fluffs.au~~ (*Fixed*)
- ~~folksocial.org~~ (*[Fixed](https://drive.proton.me/urls/ZMYAJPDF54#II2wUrd7FITp)*)
- ~~forestver.se~~ (*Fixed*)
- ~~forum-lucifer.com~~ (*Fixed*)
- ~~foss.place~~ (*[Fixed](https://old.mermaid.town/@futzle/111950327071885006)*)
- ~~fpl.social~~ (*Fixed*)
- ~~freemasonry.social~~ (*Fixed*)
- ~~freie-re.de~~ (*[Fixed](https://freie-re.de/@mastoadmin/111945738954430760)*)
- ~~friendsyu.me~~ (*[Fixed](https://friendsyu.me/notes/718dadc340bad251d7df82db)*)
- ~~gametoots.de~~ (*[Fixed](https://drive.proton.me/urls/ZMYAJPDF54#II2wUrd7FITp)*)
- ~~gervtuber.de~~ (*Fixed*)
- ~~glasgow.social~~ (*Fixed*)
- ~~graeber.social~~ (*Fixed*)
- ~~groupsebelah.com~~ (*Fixed*)
- ~~home.speakfree.social~~ (*[Fixed](https://drive.proton.me/urls/ZMYAJPDF54#II2wUrd7FITp)*)
- ~~honk.masto.host~~ (*Fixed*)
- ~~iaccessibility.social~~ (*Fixed*)
- ~~idic.social~~ (*Fixed*)
- ~~independent-media.co.uk~~ (*Fixed*)
- ~~ioc.exchange~~ (*Fixed*)
- ~~ipv6.social~~ (*Fixed*)
- ~~kohodon.fedicity.net~~ (*Fixed*)
- ~~kommunismus.social~~ (*Fixed*)
- ~~kopimi.space~~ (*Fixed*)
- ~~krems.social~~ (*[Fixed](https://old.mermaid.town/@futzle/111950327071885006)*)
- ~~library.love~~ (*Fixed*)
- ~~m.corduba.tech~~ (*Fixed*)
- ~~m.kog.to~~ (*Fixed*)
- ~~m.mxin.moe~~ (*[Fixed](https://m.mxin.moe/notes/9pru8c2off9343gb)*)
- ~~m.qqs.tw~~ (*Fixed*)
- ~~madworld.social~~ (*[Fixed](https://madworld.social/@paulgeller/111948481048282743)*)
- ~~makersocial.online~~ (*Fixed*)
- ~~mas.atmx.ca~~ (*Fixed*) 
- ~~mastdn.social~~ (*[Fixed](https://mastdn.social/@Chris/111969388188144272)*)
- ~~mastnode.faith~~ (*Fixed*)
- ~~masto.ukrainedao.love~~ (*Fixed*)
- ~~mastodon-7ecc009c.cloudplane.app~~ (*[Fixed](https://mastodon.social/@jgillich/111954534135620431)*)
- ~~mastodon-belgium.be~~ (*[Fixed](https://old.mermaid.town/@futzle/111950327071885006)*)
- ~~mastodon-ero.xyz~~ (*Fixed*)
- ~~mastodon-swiss.org~~ (*Fixed*)
- ~~mastodon.acm.org~~ (*[Fixed](https://toot.io/@jan/111954641602936850)*)
- ~~mastodon.ashevillains.org~~ (*Fixed*)
- ~~mastodon.berlin~~ (*[Fixed](https://mastodon.berlin/@christoph/111969269170766570)*)
- ~~mastodon.caruhel.fr~~ (*Fixed*)
- ~~mastodon.chrisduffley.com~~ (*[Fixed](https://old.mermaid.town/@futzle/111950327071885006)*)
- ~~mastodon.com.py~~ (*Fixed*)
- ~~mastodon.creation.md~~ (*[Fixed](https://drive.proton.me/urls/ZMYAJPDF54#II2wUrd7FITp)*)
- ~~mastodon.education~~ (*Fixed*)
- ~~mastodon.free-solutions.org~~ (*Fixed*)
- ~~mastodon.integrata-stiftung.de~~ (*Fixed*)
- ~~mastodon.joaoleitao.org~~ (*Fixed*)
- ~~mastodon.linuxmuster.net~~ (*[Fixed](https://drive.proton.me/urls/ZMYAJPDF54#II2wUrd7FITp)*)
- ~~mastodon.london~~ (*[Fixed](https://drive.proton.me/urls/ZMYAJPDF54#II2wUrd7FITp)*)
- ~~mastodon.lookbusy.org~~ (*Fixed*)
- ~~mastodon.mg~~ (*[Fixed](https://mastodon.mg/@sysadmin/111956770673419378)*)
- ~~mastodon.miri.site~~ (*Fixed*)
- ~~mastodon.my~~ (*Fixed*)
- ~~mastodon.preppers-shelter.nl~~ (*Fixed*)
- ~~mastodon.r3networks.uk~~ (*Fixed*)
- ~~mastodon.saarland~~ (*Fixed*)
- ~~mastodon.snmsoc.org~~ (*Fixed*)
- ~~mastodon.starnet.cz~~ (*[Fixed](https://mastodon.starnet.cz/@darius/111948349617265733)*)
- ~~mastodon.svgun.ru~~ (*Fixed*)
- ~~mastodon.tn~~ (*Fixed*)
- ~~mastodon.unpluggedrva.com~~ (*Fixed*)
- ~~mastodon.wg0.xyz~~ (*Fixed*)
- ~~mastodon.wssmagazine.com~~ (*Fixed*)
- ~~mastodon.zorqz.com~~ (*[Fixed](https://drive.proton.me/urls/ZMYAJPDF54#II2wUrd7FITp)*)
- ~~mastodonters.nl~~ (*Fixed*)
- ~~mastonederland.nl~~ (*Fixed*)
- ~~mentalhealth-masto.com~~ (*Fixed*)
- ~~meow.lgbt~~ (*[Fixed](https://meow.lgbt/@cassaundra/111948757046811977)*)
- ~~modelrailroadballast.com~~ (*Fixed*)
- ~~molaguay.xyz~~ (*Fixed*)
- ~~motern.media~~ (*Fixed*)
- ~~moth.social~~ (*Fixed*)
- ~~mstdn.at~~ (*Fixed*)
- ~~mstdn.funil.de~~ (*Fixed*)
- ~~mstdn.xicon.eu~~ (*Fixed*)
- ~~nafo.uk~~ (*Fixed*)
- ~~naturalstate.social~~ (*Fixed*)
- ~~netcup.social~~ (*Fixed*)
- ~~neuss.social~~ (*Fixed*)
- ~~nog.community~~ (*Fixed*)
- ~~nycity.social~~ (*[Fixed](https://drive.proton.me/urls/ZMYAJPDF54#II2wUrd7FITp)*)
- ~~occitania.social~~ (*Fixed*)
- ~~odenwald.social~~ (*[Fixed](https://odenwald.social/@thierolfOrg/111952822485653582)*)
- ~~opensimsocial.com~~ (*[Fixed](https://drive.proton.me/urls/ZMYAJPDF54#II2wUrd7FITp)*)
- ~~osten.social~~ (*[Fixed](https://drive.proton.me/urls/ZMYAJPDF54#II2wUrd7FITp)*)
- ~~owo.town~~ (*Fixed*)
- ~~parkfans.network~~ (*Fixed*)
- ~~phyrexia.ru~~ (*Fixed*)
- ~~piaille.fr~~ (*[Fixed](https://piaille.fr/@thibault/111940950007632713)*)
- ~~pkm.social~~ (*Fixed*)
- ~~planetearth.social~~ (*[Fixed](https://planetearth.social/@leon/111940469269635302)*)
- ~~pointbob.org~~ (*Fixed*)
- ~~portside.social~~ (*[Fixed](https://portside.social/@ps_social_admin/111964603874942602)*)
- ~~pouet.evolix.org~~ (*Fixed*)
- ~~prf.me~~ (*Fixed*)
- ~~pxlmo.net~~ (*[Fixed](https://drive.proton.me/urls/ZMYAJPDF54#II2wUrd7FITp)*)
- ~~qa.social~~ (*Fixed*)
- ~~quakers.social~~ (*Fixed*)
- ~~queer.dev~~ (*[Fixed](https://queer.dev/@furioursus/111953713241732551)*)
- ~~rabbitrabbitbrownrabbit.hostdon.ne.jp~~ (*Fixed*)
- ~~redpawcollective.co~~ (*[Fixed](https://old.mermaid.town/@futzle/111950327071885006)*)
- ~~redwings.social~~ (*Fixed*)
- ~~rettiwtkcuf.social~~ (*[Fixed](https://rettiwtkcuf.social/@rfrederick/111948587691795517)*)
- ~~rope-access-work.com~~ (*Fixed*)
- ~~s-h.social~~ (*Fixed*)
- ~~sector25.de~~ (*Fixed*)
- ~~selfhosted.cafe~~ (*Fixed*)
- ~~semiosen.de~~ (*Fixed*)
- ~~shotgunlife.social~~ (*[Fixed](https://drive.proton.me/urls/ZMYAJPDF54#II2wUrd7FITp)*)
- ~~so.eddyn.net~~ (*Fixed*)
- ~~social.bigcavemaps.com~~ (*Fixed*)
- ~~social.boom.army~~ (*Fixed*)
- ~~social.cezeri.tech~~ (*[Fixed](https://drive.proton.me/urls/ZMYAJPDF54#II2wUrd7FITp)*)
- ~~social.consoledated.com~~ (*Fixed*)
- ~~social.esmarconf.org~~ (*[Fixed](https://social.esmarconf.org/@chris/111952126816687562)*)
- ~~social.foederiert.de~~ (*[Fixed](https://drive.proton.me/urls/ZMYAJPDF54#II2wUrd7FITp)*)
- ~~social.kyiv.dcomm.net.ua~~ (*Fixed*)
- ~~social.learntosolveit.com~~ (*Fixed*)
- ~~social.nofftopia.com~~ (*Fixed*)
- ~~social.phoenixradio1208.com~~ (*Fixed*)
- ~~social.pogo.community~~ (*[Fixed](https://drive.proton.me/urls/ZMYAJPDF54#II2wUrd7FITp)*)
- ~~social.purrucker.de~~ (*Fixed*)
- ~~social.spicysources.de~~ (*Fixed*)
- ~~social.tcpcat.net~~ (*Fixed*)
- ~~social.territorisostenibili.org~~ (*Fixed*)
- ~~social.uggs.io~~ (*[Fixed](https://social.uggs.io/@chris/111951500021651571)*)
- ~~sotl.social~~ (*Fixed*)
- ~~spurlock.social~~ (*[Fixed](https://drive.proton.me/urls/ZMYAJPDF54#II2wUrd7FITp)*)
- ~~squabble.org~~ (*[Fixed](https://drive.proton.me/urls/ZMYAJPDF54#II2wUrd7FITp)*)
- ~~squawk.mytransponder.com~~ (*[Fixed](https://squawk.mytransponder.com/@chiefpilot/111941934637959462)*)
- ~~syringa.social~~ (*Fixed*)
- ~~tabletop.vip~~ (*Fixed*)
- ~~teamhydra.social~~ (*Fixed*)
- ~~terapeldigitaal.nl~~ (*Fixed*)
- ~~terere.social~~ (*[Fixed](https://drive.proton.me/urls/ZMYAJPDF54#II2wUrd7FITp)*)
- ~~thebigeasy.space~~ (*[Fixed](https://drive.proton.me/urls/ZMYAJPDF54#II2wUrd7FITp)*)
- ~~themeparks.social~~ (*Fixed*)
- ~~thewiring.com~~ (*[Fixed](https://drive.proton.me/urls/ZMYAJPDF54#II2wUrd7FITp)*)
- ~~ticos.social~~ (*Fixed*)
- ~~toot.fan~~ (*Fixed*)
- ~~toot.poedelwitz.de~~ (*Fixed*)
- ~~toot.quest~~ (*Fixed*)
- ~~tootnet.nl~~ (*Fixed*)
- ~~tribe.net~~ (*Fixed*)
- ~~twitchfr.social~~ (*Fixed*)
- ~~utter.online~~ (*Fixed*)
- ~~vacatureforum.nl~~ (*Fixed*)
- ~~varwest.fr~~ (*Fixed*)
- ~~vasra.masto.host~~ (*Fixed*)
- ~~vigaucho.eu~~ (*[Fixed](https://drive.proton.me/urls/ZMYAJPDF54#II2wUrd7FITp)*)
- ~~wehavecookies.social~~ (*[Fixed](https://wehavecookies.social/@admin/111939992679250475)*)
- ~~westen.social~~ (*Fixed*)
- ~~whitesmokebbq.social~~ (*Fixed*)
- ~~witten.social~~ (*[Fixed](https://drive.proton.me/urls/ZMYAJPDF54#II2wUrd7FITp)*)
- ~~worldnl.com~~ (*Fixed*)
- ~~worldtravel.photos~~ (*Fixed*)
- ~~xn--zck4ad5f2e.xn--q9jyb4c~~ (*Fixed*)
- ~~xreality.social~~ (*Fixed*)
- ~~zettel.haus~~ (*Fixed*)
- ~~zirk.us~~ (*Fixed*)



**Thank you for participating in the Fediverse Experiment!** Keep calm and rest a little after this huge amount of work! <br/> <br/>
Yours in solidarity, <br/>
[Erik Uden](https://erikuden.com) <br/>
*Creator of mastodon.de*
*Admin of troet.cafe*