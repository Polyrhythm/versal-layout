# Versal gadget launchers

This contains the different launchers for gadgets on [Versal](versal.com). Currently we have the following types of launchers, which can be set by specifying `"launcher": "some-launcher-name"` in the gadget's `manifest.json`:

- [iframe](iframe-launcher), the Iframe Launcher. It loads a gadget's HTML file inside an iframe. This is the only launcher you can currently use for new gadgets.
- [legacy](legacy-launcher), the Legacy Launcher. It maintains compatibility for earlier developed gadgets. New gadgets cannot use this launcher.

All code is licensed under the [MIT License](LICENSE).

## Changelog
- **0.3.3** Legacy Launcher: only fire setAttributes when `editing-allowed` is set (https://github.com/Versal/versal-gadget-launchers/pull/35)
- **0.3.2** Legacy Launcher: more changed attributes fixes (https://github.com/Versal/versal-gadget-launchers/pull/30)
- **0.3.1** Legacy Launcher: only send changed attributes to player (https://github.com/Versal/versal-gadget-launchers/pull/29)
