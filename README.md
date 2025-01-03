# tauri-config
```json
{
  "$schema": "../gen/schemas/desktop-schema.json",
  "identifier": "default",
  "description": "Capability for the main window",
  "windows": ["main"],
  "permissions": [
    "core:default",
    "opener:default",
    "core:default",
    "core:app:default",
    "core:app:allow-app-hide",
    "core:app:allow-app-show",
    "core:app:allow-default-window-icon",
    "core:app:allow-name",
    "core:app:allow-set-app-theme",
    "core:app:allow-tauri-version",
    "core:app:allow-version",
    "core:app:deny-app-hide",
    "core:app:deny-app-show",
    "core:app:deny-default-window-icon",
    "core:app:deny-name",
    "core:app:deny-set-app-theme",
    "core:app:deny-tauri-version",
    "core:app:deny-version",
    "core:event:default",
    "core:event:allow-emit",
    "core:event:allow-emit-to",
    "core:event:allow-listen",
    "core:event:allow-unlisten",
    "core:event:deny-emit",
    "core:event:deny-emit-to",
    "core:event:deny-listen",
    "core:event:deny-unlisten",
    "core:image:default",
    "core:image:allow-from-bytes",
    "core:image:allow-from-path",
    "core:image:allow-new",
    "core:image:allow-rgba",
    "core:image:allow-size",
    "core:image:deny-from-bytes",
    "core:image:deny-from-path",
    "core:image:deny-new",
    "core:image:deny-rgba",
    "core:image:deny-size",
    "core:menu:default",
    "core:menu:allow-append",
    "core:menu:allow-create-default",
    "core:menu:allow-get",
    "core:menu:allow-insert",
    "core:menu:allow-is-checked",
    "core:menu:allow-is-enabled",
    "core:menu:allow-items",
    "core:menu:allow-new",
    "core:menu:allow-popup",
    "core:menu:allow-prepend",
    "core:menu:allow-remove",
    "core:menu:allow-remove-at",
    "core:menu:allow-set-accelerator",
    "core:menu:allow-set-as-app-menu",
    "core:menu:allow-set-as-help-menu-for-nsapp",
    "core:menu:allow-set-as-window-menu",
    "core:menu:allow-set-as-windows-menu-for-nsapp",
    "core:menu:allow-set-checked",
    "core:menu:allow-set-enabled",
    "core:menu:allow-set-icon",
    "core:menu:allow-set-text",
    "core:menu:allow-text",
    "core:menu:deny-append",
    "core:menu:deny-create-default",
    "core:menu:deny-get",
    "core:menu:deny-insert",
    "core:menu:deny-is-checked",
    "core:menu:deny-is-enabled",
    "core:menu:deny-items",
    "core:menu:deny-new",
    "core:menu:deny-popup",
    "core:menu:deny-prepend",
    "core:menu:deny-remove",
    "core:menu:deny-remove-at",
    "core:menu:deny-set-accelerator",
    "core:menu:deny-set-as-app-menu",
    "core:menu:deny-set-as-help-menu-for-nsapp",
    "core:menu:deny-set-as-window-menu",
    "core:menu:deny-set-as-windows-menu-for-nsapp",
    "core:menu:deny-set-checked",
    "core:menu:deny-set-enabled",
    "core:menu:deny-set-icon",
    "core:menu:deny-set-text",
    "core:menu:deny-text",
    "core:path:default",
    "core:path:allow-basename",
    "core:path:allow-dirname",
    "core:path:allow-extname",
    "core:path:allow-is-absolute",
    "core:path:allow-join",
    "core:path:allow-normalize",
    "core:path:allow-resolve",
    "core:path:allow-resolve-directory",
    "core:path:deny-basename",
    "core:path:deny-dirname",
    "core:path:deny-extname",
    "core:path:deny-is-absolute",
    "core:path:deny-join",
    "core:path:deny-normalize",
    "core:path:deny-resolve",
    "core:path:deny-resolve-directory",
    "core:resources:default",
    "core:resources:allow-close",
    "core:resources:deny-close",
    "core:tray:default",
    "core:tray:allow-get-by-id",
    "core:tray:allow-new",
    "core:tray:allow-remove-by-id",
    "core:tray:allow-set-icon",
    "core:tray:allow-set-icon-as-template",
    "core:tray:allow-set-menu",
    "core:tray:allow-set-show-menu-on-left-click",
    "core:tray:allow-set-temp-dir-path",
    "core:tray:allow-set-title",
    "core:tray:allow-set-tooltip",
    "core:tray:allow-set-visible",
    "core:tray:deny-get-by-id",
    "core:tray:deny-new",
    "core:tray:deny-remove-by-id",
    "core:tray:deny-set-icon",
    "core:tray:deny-set-icon-as-template",
    "core:tray:deny-set-menu",
    "core:tray:deny-set-show-menu-on-left-click",
    "core:tray:deny-set-temp-dir-path",
    "core:tray:deny-set-title",
    "core:tray:deny-set-tooltip",
    "core:tray:deny-set-visible",
    "core:webview:default",
    "core:webview:allow-clear-all-browsing-data",
    "core:webview:allow-create-webview",
    "core:webview:allow-create-webview-window",
    "core:webview:allow-get-all-webviews",
    "core:webview:allow-internal-toggle-devtools",
    "core:webview:allow-print",
    "core:webview:allow-reparent",
    "core:webview:allow-set-webview-background-color",
    "core:webview:allow-set-webview-focus",
    "core:webview:allow-set-webview-position",
    "core:webview:allow-set-webview-size",
    "core:webview:allow-set-webview-zoom",
    "core:webview:allow-webview-close",
    "core:webview:allow-webview-hide",
    "core:webview:allow-webview-position",
    "core:webview:allow-webview-show",
    "core:webview:allow-webview-size",
    "core:webview:deny-clear-all-browsing-data",
    "core:webview:deny-create-webview",
    "core:webview:deny-create-webview-window",
    "core:webview:deny-get-all-webviews",
    "core:webview:deny-internal-toggle-devtools",
    "core:webview:deny-print",
    "core:webview:deny-reparent",
    "core:webview:deny-set-webview-background-color",
    "core:webview:deny-set-webview-focus",
    "core:webview:deny-set-webview-position",
    "core:webview:deny-set-webview-size",
    "core:webview:deny-set-webview-zoom",
    "core:webview:deny-webview-close",
    "core:webview:deny-webview-hide",
    "core:webview:deny-webview-position",
    "core:webview:deny-webview-show",
    "core:webview:deny-webview-size",
    "core:window:default",
    "core:window:allow-available-monitors",
    "core:window:allow-center",
    "core:window:allow-close",
    "core:window:allow-create",
    "core:window:allow-current-monitor",
    "core:window:allow-cursor-position",
    "core:window:allow-destroy",
    "core:window:allow-get-all-windows",
    "core:window:allow-hide",
    "core:window:allow-inner-position",
    "core:window:allow-inner-size",
    "core:window:allow-internal-toggle-maximize",
    "core:window:allow-is-closable",
    "core:window:allow-is-decorated",
    "core:window:allow-is-enabled",
    "core:window:allow-is-focused",
    "core:window:allow-is-fullscreen",
    "core:window:allow-is-maximizable",
    "core:window:allow-is-maximized",
    "core:window:allow-is-minimizable",
    "core:window:allow-is-minimized",
    "core:window:allow-is-resizable",
    "core:window:allow-is-visible",
    "core:window:allow-maximize",
    "core:window:allow-minimize",
    "core:window:allow-monitor-from-point",
    "core:window:allow-outer-position",
    "core:window:allow-outer-size",
    "core:window:allow-primary-monitor",
    "core:window:allow-request-user-attention",
    "core:window:allow-scale-factor",
    "core:window:allow-set-always-on-bottom",
    "core:window:allow-set-always-on-top",
    "core:window:allow-set-background-color",
    "core:window:allow-set-badge-count",
    "core:window:allow-set-badge-label",
    "core:window:allow-set-closable",
    "core:window:allow-set-content-protected",
    "core:window:allow-set-cursor-grab",
    "core:window:allow-set-cursor-icon",
    "core:window:allow-set-cursor-position",
    "core:window:allow-set-cursor-visible",
    "core:window:allow-set-decorations",
    "core:window:allow-set-effects",
    "core:window:allow-set-enabled",
    "core:window:allow-set-focus",
    "core:window:allow-set-fullscreen",
    "core:window:allow-set-icon",
    "core:window:allow-set-ignore-cursor-events",
    "core:window:allow-set-max-size",
    "core:window:allow-set-maximizable",
    "core:window:allow-set-min-size",
    "core:window:allow-set-minimizable",
    "core:window:allow-set-overlay-icon",
    "core:window:allow-set-position",
    "core:window:allow-set-progress-bar",
    "core:window:allow-set-resizable",
    "core:window:allow-set-shadow",
    "core:window:allow-set-size",
    "core:window:allow-set-size-constraints",
    "core:window:allow-set-skip-taskbar",
    "core:window:allow-set-theme",
    "core:window:allow-set-title",
    "core:window:allow-set-title-bar-style",
    "core:window:allow-set-visible-on-all-workspaces",
    "core:window:allow-show",
    "core:window:allow-start-dragging",
    "core:window:allow-start-resize-dragging",
    "core:window:allow-theme",
    "core:window:allow-title",
    "core:window:allow-toggle-maximize",
    "core:window:allow-unmaximize",
    "core:window:allow-unminimize",
    "core:window:deny-available-monitors",
    "core:window:deny-center",
    "core:window:deny-close",
    "core:window:deny-create",
    "core:window:deny-current-monitor",
    "core:window:deny-cursor-position",
    "core:window:deny-destroy",
    "core:window:deny-get-all-windows",
    "core:window:deny-hide",
    "core:window:deny-inner-position",
    "core:window:deny-inner-size",
    "core:window:deny-internal-toggle-maximize",
    "core:window:deny-is-closable",
    "core:window:deny-is-decorated",
    "core:window:deny-is-enabled",
    "core:window:deny-is-focused",
    "core:window:deny-is-fullscreen",
    "core:window:deny-is-maximizable",
    "core:window:deny-is-maximized",
    "core:window:deny-is-minimizable",
    "core:window:deny-is-minimized",
    "core:window:deny-is-resizable",
    "core:window:deny-is-visible",
    "core:window:deny-maximize",
    "core:window:deny-minimize",
    "core:window:deny-monitor-from-point",
    "core:window:deny-outer-position",
    "core:window:deny-outer-size",
    "core:window:deny-primary-monitor",
    "core:window:deny-request-user-attention",
    "core:window:deny-scale-factor",
    "core:window:deny-set-always-on-bottom",
    "core:window:deny-set-always-on-top",
    "core:window:deny-set-background-color",
    "core:window:deny-set-badge-count",
    "core:window:deny-set-badge-label",
    "core:window:deny-set-closable",
    "core:window:deny-set-content-protected",
    "core:window:deny-set-cursor-grab",
    "core:window:deny-set-cursor-icon",
    "core:window:deny-set-cursor-position",
    "core:window:deny-set-cursor-visible",
    "core:window:deny-set-decorations",
    "core:window:deny-set-effects",
    "core:window:deny-set-enabled",
    "core:window:deny-set-focus",
    "core:window:deny-set-fullscreen",
    "core:window:deny-set-icon",
    "core:window:deny-set-ignore-cursor-events",
    "core:window:deny-set-max-size",
    "core:window:deny-set-maximizable",
    "core:window:deny-set-min-size",
    "core:window:deny-set-minimizable",
    "core:window:deny-set-overlay-icon",
    "core:window:deny-set-position",
    "core:window:deny-set-progress-bar",
    "core:window:deny-set-resizable",
    "core:window:deny-set-shadow",
    "core:window:deny-set-size",
    "core:window:deny-set-size-constraints",
    "core:window:deny-set-skip-taskbar",
    "core:window:deny-set-theme",
    "core:window:deny-set-title",
    "core:window:deny-set-title-bar-style",
    "core:window:deny-set-visible-on-all-workspaces",
    "core:window:deny-show",
    "core:window:deny-start-dragging",
    "core:window:deny-start-resize-dragging",
    "core:window:deny-theme",
    "core:window:deny-title",
    "core:window:deny-toggle-maximize",
    "core:window:deny-unmaximize",
    "core:window:deny-unminimize",
    "opener:default",
    "opener:allow-default-urls",
    "opener:allow-open-path",
    "opener:allow-open-url",
    "opener:allow-reveal-item-in-dir",
    "opener:deny-open-path",
    "opener:deny-open-url",
    "opener:deny-reveal-item-in-dir"
  ]
}

```
