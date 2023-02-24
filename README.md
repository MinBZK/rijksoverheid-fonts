⚠️ This package may be removed at any time

## Getting started

⚠️ Before using this package make sure you have permission to use it, check [rijkshuisstijl.nl](https://www.rijkshuisstijl.nl/) for more information.

### Installation

```
yarn install https://github.com/MinBZK/rijksoverheid-fonts
npm install https://github.com/MinBZK/rijksoverheid-fonts
```

### Usage

After installation you can now import the font in your code

```JavaScript
import "rijksoverheid-fonts"; // imports serif and sans-serif

// Or if you only want a specific variation
import "rijksoverheid-fonts/sans"; // imports only sans or:
import "rijksoverheid-fonts/serif"; // imports only serif

```

After which you can set the font

```css
body {
  font-family: Rijksoverheid Sans Web Text;
}

h1 {
  font-family: Rijksoverheid Serif Web Text;
}
```

## Copyright

Copyright belongs to Rijksoverheid, visit [Rijkshuisstijl](https://www.rijkshuisstijl.nl/over-de-rijkshuisstijl/auteursrecht-rijkshuisstijl) for more information
