# leven-min2

An extremely minimalist theme for the blogging framework [Leven].

```sh
leven theme daboross/leven-min2
```

Here's a [demo].

The design is based off of [`b.m.f.w`] (warning: swearing).

This repository's organization is copied from the [Twelve] Leven theme. The
Twelve theme looks great. It's slightly less minimal, although that's probably
sane.

## Configuration

`leven-min2` allows configuration of the "archive" name in the header. If unspecified, `archive` is used.

With it's basis off of [Twelve], `leven-min2` also allows for custom navigation links.

```toml
# Omit for default "archive" value.
archive_name = "archive"

# Add a [[links]] block for each of your navigation links.
[[links]]
name = "github"
url = "https://github.com/"
```

## Features

- Extreme minimalism
- All links are relative, so you can deploy as a sub-page of a larger site

## Dependencies

- Internet Explorer 7 or better browser (IE6 and below will still render the site, it will just not have the content allignment)

[Level]: https://github.com/quadrupleslap/leven
[demo]: http://daboross.net/leven-min2
[Twelve]: https://github.com/quadrupleslap/twelve
[`b.m.f.w.`]: http://bettermotherfuckingwebsite.com/
