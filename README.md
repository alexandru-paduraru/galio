# [galio](https://www.galio.io) [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social&logo=twitter)](https://twitter.com/home?status=Galio,%20a%20free%20and%20beautiful%20UI%20framework%20https%3A//galio.io/%20%23reactnative%20%23react%20%23design%20%23developers%20%23freebie%20via%20%40CreativeTim)

[![GitHub issues](https://img.shields.io/github/issues/galio-org/galio.svg?style=popout)](https://github.com/galio-org/galio)

Galio is a 100% free and open source project, licensed under MIT. It will always remain free to use, powered by a massive world-wide community. 
Carefully crafted. Ready-made components, typography, and a gorgeous base theme that adaps to each project. You'll be building in style.
Built with real app examples, component demos, guides, and how-to's to get you up and running with mobile apps faster than ever before.

## Table of Contents
* [Quick start](#quick-start)
* [Examples](#examples)
* [Documentation](#documentation)
* [Resources](#resources)
* [Reporting Issues](#reporting-issues)
* [Licensing](#licensing)
* [Useful Links](#useful-links)

## Quick Start

#### 1. Project Setup
```bash
git clone https://github.com/galio-org/galio.git
cd galio
npm install or yarn install
```

#### 2. Project testing
Terminal cli:
`npm run ios` or `yarn run ios`

User our iOS or Android app to directly view Expo projects on your phone.

[Expo iOS app](https://itunes.apple.com/us/app/expo-client/id982107779?mt=8)

[Expo Android app](https://play.google.com/store/apps/details?id=host.exp.exponent&hl=en)

## Examples

Here we will showcase some screens and some sample code of how we've used Galio in order to create them.

![Dashboard screen](http://oi63.tinypic.com/245g5jq.jpg)

```
renderCard = (props, index) => {
    const gradientColors = index % 2 ? GRADIENT_PINK : GRADIENT_BLUE;

    return (
      <Block row center card shadow space="between" style={styles.card} key={props.title}>
        <Gradient
          start={[0.45, 0.45]}
          end={[0.90, 0.90]}
          colors={gradientColors}
          style={[styles.gradient, styles.left]}
        >
          <Icon
            size={BASE_SIZE}
            name={props.icon}
            color={COLOR_WHITE}
            family={props.iconFamily}
          />
        </Gradient>

        <Block flex>
          <Text h5>{props.title}</Text>
          <Text muted>{props.subtitle}</Text>
        </Block>
        <Button style={styles.right}>
          <Icon size={BASE_SIZE * 1.5} name="ios-arrow-forward" family="Ionicons" color={COLOR_GREY} />
        </Button>
      </Block>
    );
  }
```

## Documentation

The documentation for Galio is hosted at our [our website](https://galio.io)

## Resources

* Website: [https://galio.io]
* Expo: [https://expo.io]
* Issues: [GitHub Issues Page](https://github.com/galio-org/galio/issues)


## Reporting Issues

We use GitHub Issues as the official bug tracker for Galio. Here are some advices for our users that want to report an issue:

1. Make sure that you are using the latest version of Galio. Check for your fork's master branch status and see if it's up to date with the upstream/master (our repository)
2. Provide us with reproductible steps for the issue.
3. Some issues may be platform specific, so specifying what platform and if it's a simulator or a hardware device will help a lot.

## Licensing

* Licensed under MIT ([https://github.com/galio-org/galio/blob/master/LICENSE])

## Useful Links

Tutorials: <https://www.youtube.com/channel/UCVyTG4sCw-rOvB9oHkzZD1w>

Freebies from Creative Tim: <https://www.creative-tim.com/products>

© 2018 [Galio](https://galio.io), made with love for apps.