# Troubleshooting

## Requirements

Under the hood yubaba uses the [Web Animations API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Animations_API). Make sure you [have a polyfill](https://github.com/web-animations/web-animations-js) if targetting browsers that don't support it.

Bring your own Promise polyfill.

## Images and variable height elements

If you have elements that can change height while an animation is progressing the end position might be out of place. Ensure your page has a reasonable amount of fixed size elements where needed to keep the illusion. [There is an issue to investigate if a fix is possible.](https://github.com/madou/yubaba/issues/14)

# Need Help?

If you're struggling to get started [make an issue](https://github.com/madou/yubaba/issues/new) or [tweet me @itsmadou](twitter.com/itsmadou), and we can add solutions to common problems here.