# Shigeko Commands

# ->Substitute the . for whatever the command prefix is set for your server.<-

# [Format of list is: Command|Usage|Example]
		
##					  	Gambling

.$ .currency .$$ .$$$ .cash .cur|Check how much currency a person has. (Defaults to yourself)|.$ or .$ @SomeGuy

.betflip .bf|Bet to guess will the result be heads or tails.|.bf 5 heads or .bf 3 t

.claimwaifu .claim|Claim a waifu for yourself by spending currency. You must spend at least 10% more than her current value unless she set  .affinity towards you.|.claim 50 @Himesama

.divorce|Releases your claim on a specific waifu. You will get some of the money you've spent back unless that waifu has an affinity towards you. 6 hours cooldown.|.divorce @CheatingSloot

.affinity|Sets your affinity towards someone you want to be claimed by. Setting affinity will reduce their .claim on you by 20%. You can leave second argument empty to clear your affinity. 30 minutes cooldown.|.affinity @MyHusband or  .affinity

.waifus .waifulb|Shows top 9 waifus. You can specify another page to show other waifus.|.waifus or .waifulb 3

.waifuinfo .waifustats|Shows waifu stats for a target person. Defaults to you if no user is provided.|.waifuinfo @MyCrush or  .waifuinfo

.wheeloffortune .wheel|Bets a certain amount of currency on the wheel of fortune. Wheel can stop on one of many different multipliers. Won amount is rounded down to the nearest whole number.|.wheel 5
		
##					  	Games

.choose|Chooses a thing from a list of things|.choose Get up;Sleep;Sleep more

.8ball|Ask the 8ball a yes/no question.|.8ball should I do something

.rps|Play a game of Rocket-Paperclip-Scissors with Nadeko.|.rps scissors

.pick|Picks the currency planted in this channel. 60 seconds cooldown.|.pick

.plant|Spend an amount of currency to plant it in this channel. Default is 1. (If bot is restarted or crashes, the currency will be lost)|.plant or .plant 5
		
##						Pokemon Battles

.attack|Attacks a target with the given move. Use .movelist to see a list of moves your type can use.|.attack "vine whip" @someguy

.movelist .ml|Lists the moves you are able to use|.ml

.type|Get the poketype of the target.|.type @someone

.settype|Set your poketype. Costs a Chi. Provide no arguments to see a list of available types.|.settype fire or .settype

##            Searches

.lolban|Shows top banned champions ordered by ban rate.|.lolban

.weather .we|Shows weather data for a specified city. You can also specify a country after a comma.|.we Moscow, RU

.time|Shows the current time and timezone in the specified location.|.time London, UK

.youtube .yt|Searches youtubes and shows the first result|.yt query

.imdb .omdb|Queries omdb for movies or series, show first result.|.imdb Batman vs Superman

.randomcat .meow|Shows a random cat image.|.meow

.randomdog .woof|Shows a random dog image.|.woof

.image .img|Pulls the first image found using a search parameter. Use .rimg for different results.|.img cute kitten

.randomimage .rimg|Pulls a random image using a search parameter.|.rimg cute kitten

.lmgtfy|Google something for an idiot.|.lmgtfy query

.shorten|Attempts to shorten an URL, if it fails, returns the input URL.|.shorten https://google.com

.google .g|Get a Google search link for some terms.|.google query

.magicthegathering .mtg|Searches for a Magic The Gathering card.|.magicthegathering about face or  .mtg about face

.hearthstone .hs|Searches for a Hearthstone card and shows its image. Takes a while to complete.|.hs Ysera

.yodify .yoda|Translates your normal sentences into Yoda styled sentences!|.yoda my feelings hurt

.urbandict .ud|Searches Urban Dictionary for a word.|.ud Pineapple

.define .def|Finds a definition of a word.|.def heresy

.#|Searches Tagdef.com for a hashtag.|.# ff

.catfact|Shows a random catfact from http://catfacts-api.appspot.com/api/facts|.catfact

.revav|Returns a Google reverse image search for someone's avatar.|.revav @SomeGuy

.revimg|Returns a Google reverse image search for an image from a link.|.revimg Image link

.wikipedia .wiki|Gives you back a wikipedia link|.wiki query

.color|Shows you what color corresponds to that hex.|.color 00ff00

.avatar .av|Shows a mentioned person's avatar.|.av @SomeGuy

.wikia|Gives you back a wikia link|.wikia mtg Vigilance or .wikia mlp Dashy

.mal|Shows basic info from a MyAnimeList profile.|.mal straysocks

.anime .ani .aq|Queries anilist for an anime and shows the first result.|.ani aquarion evol

.manga .mang .mq|Queries anilist for a manga and shows the first result.|.mq Shingeki no kyojin

.yomama .ym|Shows a random joke from http://api.yomomma.info/|.ym

.randjoke .rj|Shows a random joke from http://tambal.azurewebsites.net/joke/random|.rj

.chucknorris .cn|Shows a random Chuck Norris joke from http://api.icndb.com/jokes/random/|.cn

.wowjoke|Get one of Kwoth's penultimate WoW jokes.|.wowjoke

.magicitem .mi|Shows a random magic item from https://1d4chan.org/wiki/List_of_/tg/%27s_magic_items|.mi

.osu|Shows osu stats for a player.|.osu Name or .osu Name taiko

.osub|Shows information about an osu beatmap.|.osub https://osu.ppy.sh/s/127712

.osu5|Displays a user's top 5 plays.|.osu5 Name

.overwatch .ow|Show's basic stats on a player (competitive rank, playtime, level etc) Region codes are: eu us cn kr|.ow us Battletag#1337 or .overwatch eu Battletag#2016
.placelist|Shows the list of available tags for the .place command.|.placelist

.place|Shows a placeholder image of a given tag. Use  .placelist to see all available tags. You can specify the width and height of the image as the last two optional arguments.|.place Cage or .place steven 500 400

.pokemon .poke|Searches for a pokemon.|.poke Sylveon

.pokemonability .pokeab|Searches for a pokemon ability.|.pokeab overgrow

.liststreams .ls|Lists all streams you are following on this server.|.ls

.checkstream .cs|Checks if a user is online on a certain streaming platform.|.cs twitch MyFavStreamer

.translate .trans|Translates from>to text. From the given language to the destination language.|.trans en>fr Hello
