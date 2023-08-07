# Adaptive-Photo-Layout

Enables adaptive photo layouts for posts and pages on Micro.blog.

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

### Support Development

[Support the development](https://paypal.me/mattslangford) of this theme and plugins.
