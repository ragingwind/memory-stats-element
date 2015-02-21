# memory-stats-element

Custom element for memory-stats . It based on [Paul Irish](https://github.com/paulirish)'s [memory-stats](https://github.com/paulirish/memory-stats.js)

![](http://i.imgur.com/bStpVsC.gif)

See the [component page](http://ragingwind.github.io/memory-stats-element) for more information.

## Installation

```
bower install ragingwind/memory-stats-element
```

## How to run

Start Chrome with `--enable-precise-memory-info` and `--enable-memory-info`

```
# Linux
google-chrome --enable-precise-memory-info --enable-memory-info

#MacOS
/Applications/Google\ Chrome.app/Contents/MacOS/Google\ Chrome --enable-precise-memory-info --enable-memory-info
```

## Usage

```
<link rel="import" href="../memory-stats-element/memory-stats-element.html">
<memory-stats-element></memory-stats-element>
<memory-stats-element style="position:fixed;right:0;bottom:0;"></memory-stats-element>
<memory-stats-element position="left-top"></memory-stats-element>
```

## Getting Started

We've put together a [guide for memory-stats](http://www.polymer-project.org/docs/start/reusableelements.html) to help get you rolling.
