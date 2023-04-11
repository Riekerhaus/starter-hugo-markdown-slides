---
title: Riekerhaus im Odenwald
date: 2019-02-05
summary: An introduction to using Wowchemy's Slides feature.
slides:
  theme: black
  highlight_style: dracula
authors: []
tags:
  - Tutorials
image:
  filename: fischbachtal.jpg
categories: []
---
# Create slides in Markdown with Wowchemy

[Wowchemy](https://wowchemy.com/) | [Documentation](https://wowchemy.com/docs/content/slides/)

- - -

## Features

<!--StartFragment-->

Die Ferienwohnung, die ich betrete, ist geräumig und lichtdurchflutet. Der Blick durch die Fenster bietet einen atemberaubenden Ausblick auf die Berge. Die Einrichtung ist modern und geschmackvoll, mit bequemen Sofas und Stühlen, die zum Entspannen einladen.

In der Küche gibt es alles, was man zum Kochen braucht. Der Kühlschrank ist groß genug, um alle Lebensmittel für eine Woche aufzubewahren. Der Esstisch ist groß genug für alle Gäste und bietet eine tolle Atmosphäre für gemütliche Mahlzeiten.

Die Schlafzimmer sind mit bequemen Betten ausgestattet, die für einen erholsamen Schlaf sorgen. Die Fenster können mit Jalousien verdunkelt werden, um einen ruhigen und dunklen Schlaf zu ermöglichen. Die Badezimmer sind sauber und modern mit Dusche oder Badewanne.

Der Balkon ist groß genug, um sich dort zu sonnen oder einen gemütlichen Abend mit Freunden und Familie zu verbringen. Ein kleiner Tisch und Stühle stehen bereit, um dort Mahlzeiten zu genießen oder einfach nur zu entspannen und die Aussicht zu genießen.

Insgesamt bietet die Ferienwohnung alles, was man für einen angenehmen Aufenthalt braucht. Sie ist sauber, modern und bietet einen atemberaubenden Ausblick auf die Berge. Ich freue mich darauf, hier ein paar Tage zu verbringen und die Umgebung zu erkunden.

<!--EndFragment-->

- - -

## Controls

* Next: `Right Arrow` or `Space`
* Previous: `Left Arrow`
* Start: `Home`
* Finish: `End`
* Overview: `Esc`
* Speaker notes: `S`
* Fullscreen: `F`
* Zoom: `Alt + Click`
* [PDF Export](https://revealjs.com/pdf-export/)

- - -

## Code Highlighting

Inline code: `variable`

Code block:

```python
porridge = "blueberry"
if porridge == "blueberry":
    print("Eating...")
```

- - -

## Math

In-line math: $x + y = z$

Block math:

$$
f\left( x \right) = ;\frac{{2\left( {x + 4} \right)\left( {x - 4} \right)}}{{\left( {x + 4} \right)\left( {x + 1} \right)}}
$$

- - -

## Fragments

Make content appear incrementally

```
{{</* fragment */>}} $\mathbf{y} =  $ {{</* /fragment */>}}
{{</* fragment */>}} $X\boldsymbol\beta$ {{</* /fragment */>}}
{{</* fragment */>}} $+ \boldsymbol\varepsilon$ {{</* /fragment */>}}
```

Press `Space` to play!

{{< fragment >}} $\mathbf{y} =  $ {{< /fragment >}}
{{< fragment >}} $X\boldsymbol\beta$ {{< /fragment >}}
{{< fragment >}} $+ \boldsymbol\varepsilon$ {{< /fragment >}}

- - -

A fragment can accept two optional parameters:

* `class`: use a custom style (requires definition in custom CSS)
* `weight`: sets the order in which a fragment appears

- - -

## Speaker Notes

Add speaker notes to your presentation

```markdown
{{%/* speaker_note */%}}

- Only the speaker can read these notes
- Press `S` key to view

{{%/* /speaker_note */%}}
```

Press the `S` key to view the speaker notes!

{{< speaker_note >}}

* Only the speaker can read these notes
* Press `S` key to view

{{< /speaker_note >}}

- - -

## Themes

* black: Black background, white text, blue links (default)
* white: White background, black text, blue links
* league: Gray background, white text, blue links
* beige: Beige background, dark text, brown links
* sky: Blue background, thin dark text, blue links

- - -

* night: Black background, thick white text, orange links
* serif: Cappuccino background, gray text, brown links
* simple: White background, black text, blue links
* solarized: Cream-colored background, dark green text, blue links

- - -

{{< slide background-image="boards.webp" >}}

## Custom Slide

Customize the slide style and background

```markdown
{{</* slide background-image="IMG-20230410-WA0004.jpg" */>}}
{{</* slide background-color="#0000FF" */>}}
{{</* slide class="my-style" */>}}
```

- - -

## Custom CSS Example

Let's make headers navy colored.

Create `assets/css/reveal_custom.css` with:

```css
.reveal section h1,
.reveal section h2,
.reveal section h3 {
  color: navy;
}
```

- - -

# Questions?

[Ask](https://discord.gg/z8wNYzb)

[Documentation](https://wowchemy.com/docs/content/slides/)