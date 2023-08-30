# Adaptive-Photo-Layout

Enables adaptive photo layouts for posts and pages on Micro.blog. Based on work by [Max Voltar](https://www.maxvoltar.com/?be).

![Adaptive Photo Layout Icon](https://github.com/MattSLangford/Adaptive-Photo-Layout/blob/main/screenshot.jpg?raw=true)

### Installation

Simply install this plugin from the Micro.blog plugin directly. Requires use of the [Tiny Theme for Micro.blog](https://tinyformicro.blog).

### Use

To use this plugin, you're required to use the following code in your post or page. There is no limit on the number of images you can include.

```
<div class="adaptive_photo_layout">
	<ul>
		<li><img src="LINK TO IMAGE 1" alt="IMAGE 1 DESCRIPTION" loading="lazy"></li>
		<li><img src="LINK TO IMAGE 2" alt="IMAGE 2 DESCRIPTION" loading="lazy"></li>
		<li><img src="LINK TO IMAGE 3" alt="IMAGE 3 DESCRIPTION" loading="lazy"></li>
		<li><img src="LINK TO IMAGE 4" alt="IMAGE 4 DESCRIPTION" loading="lazy"></li>
		<li><img src="LINK TO IMAGE 5" alt="IMAGE 5 DESCRIPTION" loading="lazy"></li>
		<li></li>
	</ul>
</div>
```

**IMPORTANT**: Notice the last `<li></li>`. It is intentionally left blank. It must exist and it must be blank.

You can additionally link any/all image(s) to larger versions (or anything else) like this:

```
<li><a href="INSERT LINK"><img src="LINK TO IMAGE" alt="IMAGE 1 DESCRIPTION" loading="lazy"></a></li>
```

### iOS/MacOS Shortcuts

Jarrod Blundy of [HeyDingus.net](https://heydingus.net) (see his [Shortcuts Library](https://heydingus.net/shortcuts)) created a pair of Shortcuts for iOS/MacOS that enables quick creation of galleries.

- [Gallery Creator](https://www.icloud.com/shortcuts/d356c88c7d924ec4b14c925febfb1fe0) (default creation)
- [Gallery Builder](https://www.icloud.com/shortcuts/111da86d6f544104936b61320da394dd) (add more photos to an existing album)

The first time you run the Shortcuts, you'll be required to entire your Micro.blog information and agree to the necessary permissions. You'll also be shown each image and given a field to add proper alt descriptions.

## Do you value this theme and plugins?

Tiny Theme and its plugins are provided free of charge to Micro.blog users. I do not receive payment from Micro.blog in any way. If you'd like to help offset expenses and ensure the future of Tiny Theme and its plugins, please consider supporting its development.

[Make a one-time Donation](https://donate.stripe.com/5kAeV7gWk9fk7aE7ss) in any amount or [setup a $5 monthly donation](https://buy.stripe.com/28odR3eOc2QWeD6cMN). Thank you!


