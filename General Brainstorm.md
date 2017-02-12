# LivingOnMars

There's a lot of science fiction around the concept of having colonies on other planets, but usually they're already underway for centuries, or they are based on things well beyond current technology or just plain fiction.

So let's think about how to kickstart a colony in our current lifetime.

## Some facts
* It takes months to travel to and from mars, give or take some more months depending on where earth/mars are positioned
* It takes 3-12 minutes for data to travel and the data rate will be low (think max 250kbps)
* Mars' rotation (and other line of sight issues) can prevent communication to go through to Earth

## Gov
The distance between Earth and Mars just makes it unrealistic to have Mars human activity to be handled by Earth. There has to be an independent governing of Mars activities by Mars inhabitants. (Of course this doesn't have to be an actual government, they just have to make sure responsibility to create a self sustaining colony is clear and organized)

## Money
As for money to exchange services and goods, one would hope they wouldn't need it, but knowing humans, they probably will. I would think Bitcoin would be a good guess, were it not for the fact that the current blockchain is well beyond being able to update over a trans-planetary Internet connection. A new chain of a Bitcoin variant will have to be introduced for Mars-only currency.

But then comes the next challenge, how are you supposed to keep you Marscoin-wallet with you, and how will it synchronize with the rest of Mars?

## Power
There's a high likelihood of initially a shared collection of solar panels to produce power during the martian day. Maybe there's some batteries, but one would have to be careful about energy consumption in the first decade either way. Will a smartphone be too much of an energy hog? Would we need a dedicated low-power smartphone?

## Local communication
Will phones be an option at all in the first place, what kind of infrastructure would they need? Maybe the simpler solution would be to setup a wifi network and have a local VOIP service.

But there's no Internet on Mars, nor are the minutes of delay and low data rates usable to maintain such a thing. There would have to be a new 'Internet', a mars-net. Obviously just in case this should be set in different IPv6 ranges than currently held on earth. Once having setup a basic DNS server and registrar (.mars tld?), people on Mars can setup their own website on the Mars-net.

## Computing
Someone should probably bring a server along with some basic LAMP software to download for people who would want to setup their server. Along with other useful software like the previously discussed VOIP, DNS and Marscoin software, perhaps even a public GIT server with Github or Gitlab.

As a server, we can probably make use of a Raspberry PI or similar device which can run Linux, but don't have the power requirements a normal PC or server would have. As available power increases on Mars, you can increase the number of PI's, or use regular computers.

## Internet cache

I would like to eventually see a cache of the Earth Internet that gets updated once in a while, or have a non-tcp based push/poll service that gets websites in large chunks onto the proxy server. In order to facilitate this, I'm not sure if we could rely on NASA's DSN unless they would want to expand or able to schedule in enough time to push websites to Mars.

The cache needs to be able to scale, and for scale one would need more and more servers and harddrives to get to Mars. So it would probably be best not to go too fast on wanting to synchronize the Internet.

Maybe a more modest approach, like for example bringing a copy of Wikipedia, and having someone update a Mars news website from news relayed from Earth to Mars.

## Social media

...
