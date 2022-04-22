<!DOCTYPE html>==$0
<html>...</head>
<body show-background-image style="backgraund-color: rgb(69, 87, 96);">
  
  <ntp-app show-background-image_=""></ntp-app>
   #shadow-root (open) ==0
  <style>...</style>
  <!--_html_templante_start_-->
  <div id="content" style="--ntp-theme-text-color: rgba(248, 249, 250, 1); --ntp-logo-color: rgba(238, 238, 238, 1);"><ntp-iframe id="oneGoogleBar" src="chrome-untrusted://new-tab-page/one-google-bar?paramsencoded=" style="clip-path: url(&quot;#oneGoogleBarClipPath&quot;); z-index: 1000;"></ntp-iframe><dom-if style="display: none;"><template is="dom-if"></template></dom-if><dom-if style="display: none;"><template is="dom-if"></template></dom-if><!-- TODO(crbug.com/1168361): Instead of hidden$="[[!logoEnabled_]]" it would
       be nicer to use a dom-if. However, that breaks
       StartupBrowserCreatorPickerNoParamsTest.ShowPickerWhenAlreadyLaunched on
       the msan builder. See crbug.com/1169070. --><ntp-logo id="logo" single-colored="" doodle-boxed_="" style="--ntp-logo-share-button-background-color:rgba(255, 255, 255, 0.3); --ntp-logo-share-button-height:13%; --ntp-logo-share-button-width:5.2%; --ntp-logo-share-button-x:92%; --ntp-logo-share-button-y:8%; --ntp-logo-box-color:rgba(7, 32, 13, 1);"></ntp-logo><ntp-realbox id="realbox" shown=""></ntp-realbox><cr-most-visited id="mostVisited" is-dark_="" visible_="" custom-links-enabled_=""></cr-most-visited><dom-if style="display: none;"><template is="dom-if"></template></dom-if><ntp-middle-slot-promo></ntp-middle-slot-promo><dom-if style="display: none;"><template is="dom-if"></template></dom-if><dom-if style="display: none;"><template is="dom-if"></template></dom-if><a id="backgroundImageAttribution" hidden=""><div id="backgroundImageAttribution1Container"><div id="linkIcon"></div><div id="backgroundImageAttribution1">
            
          </div></div><div id="backgroundImageAttribution2" hidden="">
          
        </div></a><!-- cr-button has a transparent background. This leads to incorrect
           results when a custom background is set. Therefore, wrap customize
           button in container to enfore solid background color. --><div id="customizeButtonContainer"><cr-button id="customizeButton" title="Personalizar esta página" aria-disabled="false" role="button" tabindex="0"><div id="customizeIcon"></div><div id="customizeText" hidden="">
            Personalizar Chrome
          </div></cr-button></div><div id="themeAttribution" hidden=""><div>Tema creado por</div><img src="undefined"><img></div><dom-if style="display: none;"><template></template></dom-if><div id="contentBottomSpacer"></div></div>
  <dom-if restamp="" style="display: none;"><template></template></dom-if>
  <dom-if id="customizeDialogIf" restamp="" style="display: none;"><template is="dom-if"></template></dom-if>
  <svg><defs><clipPath id="oneGoogleBarClipPath"><!-- Set an initial non-empty clip-path so the OneGoogleBar resize events
           are processed. When the clip-path is empty, it's possible for the
           OneGoogleBar to get into a state where it does not send  the
           'overlayUpdates' message which is used to populate this
           clip-path. --><rect x="-8" y="-8" width="662" height="80"></rect></clipPath></defs></svg>
  <!--_html_template_end_-->
<ntp-app show-background-image_=""></ntp-app>
  <script type="module" src="new_tab_page.js"></script>
  <link rel="stylesheet" href="chrome://resources/css/text_defaults_md.css">
  <link rel="stylesheet" href="chrome://resources/css/text_defaults_md.css">
  <dom-module id="cr-hidden-style" assetpath="chrome://resources/">
  <template>
    <style scope="cr-hidden-style">[hidden], :host([hidden]) {
  display: none !important;
}

</style>
  </template>
</dom-module>
  <dom-module id="cr-icons" assetpath="chrome://resources/">
  <template>
    <style scope="cr-icons">.icon-arrow-back {
  --cr-icon-image: url('chrome://resources/images/icon_arrow_back.svg');
}

.icon-arrow-dropdown {
  --cr-icon-image: url('chrome://resources/images/icon_arrow_dropdown.svg');
}

.icon-cancel {
  --cr-icon-image: url('chrome://resources/images/icon_cancel.svg');
}

.icon-clear {
  --cr-icon-image: url('chrome://resources/images/icon_clear.svg');
}

.icon-copy-content {
  --cr-icon-image: url('chrome://resources/images/icon_copy_content.svg');
}

.icon-delete-gray {
  --cr-icon-image: url('chrome://resources/images/icon_delete_gray.svg');
}

.icon-edit {
  --cr-icon-image: url('chrome://resources/images/icon_edit.svg');
}

.icon-picture-delete {
  --cr-icon-image: url('chrome://resources/images/icon_picture_delete.svg');
}

.icon-expand-less {
  --cr-icon-image: url('chrome://resources/images/icon_expand_less.svg');
}

.icon-expand-more {
  --cr-icon-image: url('chrome://resources/images/icon_expand_more.svg');
}

.icon-external {
  --cr-icon-image: url('chrome://resources/images/open_in_new.svg');
}

.icon-more-vert {
  --cr-icon-image: url('chrome://resources/images/icon_more_vert.svg');
}

.icon-refresh {
  --cr-icon-image: url('chrome://resources/images/icon_refresh.svg');
}

.icon-search {
  --cr-icon-image: url('chrome://resources/images/icon_search.svg');
}

.icon-settings {
  --cr-icon-image: url('chrome://resources/images/icon_settings.svg');
}

.icon-visibility {
  --cr-icon-image: url('chrome://resources/images/icon_visibility.svg');
}

.icon-visibility-off {
  --cr-icon-image: url('chrome://resources/images/icon_visibility_off.svg');
}

.subpage-arrow {
  --cr-icon-image: url('chrome://resources/images/arrow_right.svg');
}

.cr-icon {
  -webkit-mask-image: var(--cr-icon-image);
        -webkit-mask-position: center;
        -webkit-mask-repeat: no-repeat;
        -webkit-mask-size: var(--cr-icon-size);
        background-color: var(--cr-icon-color, var(--google-grey-700));
        flex-shrink: 0;
        height: var(--cr-icon-ripple-size);
        margin-inline-end: var(--cr-icon-ripple-margin);
        margin-inline-start: var(--cr-icon-button-margin-start);
        user-select: none;
        width: var(--cr-icon-ripple-size);
}

:host-context([dir=rtl]) .cr-icon {
  transform: scaleX(-1);
}

.cr-icon.no-overlap {
  margin-inline-end: 0;
        margin-inline-start: 0;
}

@media (prefers-color-scheme: dark) {
.cr-icon {
  background-color: var(--cr-icon-color, var(--google-grey-500));
}

}

</style>
  </template>
</dom-module>
  <dom-module id="cr-shared-style" assetpath="chrome://resources/">
  <template>
    <style include="cr-hidden-style cr-icons" scope="cr-shared-style">html, :host {
  --scrollable-border-color: var(--google-grey-300);
}

@media (prefers-color-scheme: dark) {
html, :host {
  --scrollable-border-color: var(--google-grey-700);
}

}

[actionable] {
  cursor: pointer;
}

.hr {
  border-top: var(--cr-separator-line);
}

iron-list.cr-separators > *:not([first]) {
  border-top: var(--cr-separator-line);
}

[scrollable] {
  border-color: transparent;
        border-style: solid;
        border-width: 1px 0;
        overflow-y: auto;
}

[scrollable].is-scrolled {
  border-top-color: var(--scrollable-border-color);
}

[scrollable].can-scroll:not(.scrolled-to-bottom) {
  border-bottom-color: var(--scrollable-border-color);
}

[scrollable] iron-list > :not(.no-outline):focus, [selectable]:focus, [selectable] > :focus {
  background-color: var(--cr-focused-item-color);
        outline: none;
}

.scroll-container {
  display: flex;
        flex-direction: column;
        min-height: 1px;
}

[selectable] > * {
  cursor: pointer;
}

.cr-centered-card-container {
  box-sizing: border-box;
        display: block;
        height: inherit;
        margin: 0 auto;
        max-width: var(--cr-centered-card-max-width);
        min-width: 550px;
        position: relative;
        width: calc(100% * var(--cr-centered-card-width-percentage));
}

.cr-container-shadow {
  box-shadow: inset 0 5px 6px -3px rgba(0, 0, 0, .4);
        height: var(--cr-container-shadow-height);
        left: 0;
        margin: 0 0 var(--cr-container-shadow-margin);
        opacity: 0;
        pointer-events: none;
        position: relative;
        right: 0;
        top: 0;
        transition: opacity 500ms;
        z-index: 1;
}

#cr-container-shadow-bottom {
  margin-bottom: 0;
        margin-top: var(--cr-container-shadow-margin);
        transform: scaleY(-1);
}

#cr-container-shadow-top.has-shadow, #cr-container-shadow-bottom.has-shadow {
  opacity: var(--cr-container-shadow-max-opacity);
}

.cr-row {
  align-items: center;
        border-top: var(--cr-separator-line);
        display: flex;
        min-height: var(--cr-section-min-height);
        padding: 0 var(--cr-section-padding);
}

.cr-row.first, .cr-row.continuation {
  border-top: none;
}

.cr-row-gap {
  padding-inline-start: 16px;
}

.cr-button-gap {
  margin-inline-start: 8px;
}

paper-tooltip {
  --paper-tooltip_-_border-radius:  var(--paper-tooltip-border-radius, 2px); --paper-tooltip_-_font-size:  92.31%; --paper-tooltip_-_font-weight:  500; --paper-tooltip_-_max-width:  330px; --paper-tooltip_-_min-width:  var(--paper-tooltip-min-width, 200px); --paper-tooltip_-_padding:  var(--paper-tooltip-padding, 10px 8px);
}

.cr-padded-text {
  padding-block-end: var(--cr-section-vertical-padding);
        padding-block-start: var(--cr-section-vertical-padding);
}

.cr-title-text {
  color: var(--cr-title-text-color);
        font-size: 107.6923%; 
        font-weight: 500;
}

.cr-secondary-text {
  color: var(--cr-secondary-text-color);
        font-weight: 400;
}

.cr-form-field-label {
  color: var(--cr-form-field-label-color);
        display: block;
        font-size: var(--cr-form-field-label-font-size);
        font-weight: 500;
        letter-spacing: .4px;
        line-height: var(--cr-form-field-label-line-height);
        margin-bottom: 8px;
}

.cr-vertical-tab {
  align-items: center;
        display: flex;
}

.cr-vertical-tab::before {
  border-radius: 0 3px 3px 0;
        content: '';
        display: block;
        flex-shrink: 0;
        height: var(--cr-vertical-tab-height, 100%);
        width: 4px;
}

.cr-vertical-tab.selected::before {
  background: var(--cr-vertical-tab-selected-color, var(--cr-checked-color));
}

:host-context([dir=rtl]) .cr-vertical-tab::before {
  transform: scaleX(-1);
}

.iph-anchor-highlight {
  background-color: var(--cr-iph-anchor-highlight-color);
}

</style>
  </template>
</dom-module>
  <dom-module id="cr-input-style" assetpath="chrome://resources/">
  <template>
    <style scope="cr-input-style">:host {
  --cr-input-background-color: var(--google-grey-100);
        --cr-input-color: var(--cr-primary-text-color);
        --cr-input-error-color: var(--google-red-600);
        --cr-input-focus-color: var(--google-blue-600);
        display: block;
        
        outline: none;
}

@media (prefers-color-scheme: dark) {
:host {
  --cr-input-background-color: rgba(0, 0, 0, .3);
          --cr-input-error-color: var(--google-red-300);
          --cr-input-focus-color: var(--google-blue-300);
}

}

:host([focused_]:not([readonly]):not([invalid])) #label {
  color: var(--cr-input-focus-color);
}

#input-container {
  border-radius: var(--cr-input-border-radius, 4px);
        overflow: hidden;
        position: relative;
        width: var(--cr-input-width, 100%);
}

#inner-input-container {
  background-color: var(--cr-input-background-color);
        box-sizing: border-box;
        padding: 0;
}

#input {
  -webkit-appearance: none;
        
        background-color: transparent;
        border: none;
        box-sizing: border-box;
        caret-color: var(--cr-input-focus-color);
        color: var(--cr-input-color);
        font-family: inherit;
        font-size: inherit;
        font-weight: inherit;
        line-height: inherit;
        min-height: var(--cr-input-min-height, auto);
        outline: none;

        
        padding-bottom: var(--cr-input-padding-bottom, 6px);
        padding-inline-end: var(--cr-input-padding-end, 8px);
        padding-inline-start: var(--cr-input-padding-start, 8px);
        padding-top: var(--cr-input-padding-top, 6px);

        text-align: inherit;
        text-overflow: ellipsis;
        width: 100%;
}

#underline {
  border-bottom: 2px solid var(--cr-input-focus-color);
        border-radius: var(--cr-input-underline-border-radius, 0);
        bottom: 0;
        box-sizing: border-box;
        display: var(--cr-input-underline-display);
        height: var(--cr-input-underline-height, 0);
        left: 0;
        margin: auto;
        opacity: 0;
        position: absolute;
        right: 0;
        transition: opacity 120ms ease-out, width 0s linear 180ms;
        width: 0;
}

:host([invalid]) #underline, :host([force-underline]) #underline, :host([focused_]) #underline {
  opacity: 1;
        transition: opacity 120ms ease-in, width 180ms ease-out;
        width: 100%;
}

</style>
  </template>
</dom-module>
  <script type="module" src="./lazy_load.js"></script>
  <dom-module id="cr-radio-button-style" assetpath="chrome://resources/">
  <template>
    <style scope="cr-radio-button-style">:host {
  --cr-radio-button-checked-color: var(--google-blue-600);
        --cr-radio-button-checked-ripple-color:
            rgba(var(--google-blue-600-rgb), .2);
        --cr-radio-button-ink-size: 40px;
        --cr-radio-button-size: 16px;
        --cr-radio-button-unchecked-color: var(--google-grey-700);
        --cr-radio-button-unchecked-ripple-color:
            rgba(var(--google-grey-600-rgb), .15);

        --ink-to-circle: calc((var(--cr-radio-button-ink-size) -
                               var(--cr-radio-button-size)) / 2);
        align-items: center;
        display: flex;
        flex-shrink: 0;
        outline: none;
}

@media (prefers-color-scheme: dark) {
:host {
  --cr-radio-button-checked-color: var(--google-blue-300);
          --cr-radio-button-checked-ripple-color:
              rgba(var(--google-blue-300-rgb), .4);
          --cr-radio-button-unchecked-color: var(--google-grey-500);
          --cr-radio-button-unchecked-ripple-color:
              rgba(var(--google-grey-300-rgb), .4);
}

}

:host([disabled]) {
  opacity: var(--cr-disabled-opacity);
        
        pointer-events: none;
}

:host(:not([disabled])) {
  cursor: pointer;
}

#labelWrapper {
  flex: 1;
        margin-inline-start: var(--cr-radio-button-label-spacing, 20px);
}

#label {
  color: inherit;
}

.disc-border, .disc, .disc-wrapper, paper-ripple {
  border-radius: 50%;
}

.disc-wrapper {
  height: var(--cr-radio-button-size);
        margin-block-start: var(--cr-radio-button-disc-margin-block-start, 0);
        position: relative;
        width: var(--cr-radio-button-size);
}

.disc-border, .disc {
  box-sizing: border-box;
        height: var(--cr-radio-button-size);
        width: var(--cr-radio-button-size);
}

.disc-border {
  border: 2px solid var(--cr-radio-button-unchecked-color);
}

:host([checked]) .disc-border {
  border-color: var(--cr-radio-button-checked-color);
}

#button:focus {
  outline: none;
}

.disc {
  background-color: transparent;
        position: absolute;
        top: 0;
        transform: scale(0);
        transition: border-color 200ms, transform 200ms;
}

:host([checked]) .disc {
  background-color: var(--cr-radio-button-checked-color);
        transform: scale(0.5);
}

paper-ripple {
  --paper-ripple-opacity: 1;  
        color: var(--cr-radio-button-unchecked-ripple-color);
        height: var(--cr-radio-button-ink-size);
        left: calc(-1 * var(--ink-to-circle));
        pointer-events: none;
        position: absolute;
        top: calc(-1 * var(--ink-to-circle));
        transition: color linear 80ms;
        width: var(--cr-radio-button-ink-size);
}

:host-context([dir=rtl]) paper-ripple {
  left: auto;
        right: calc(-1 * var(--ink-to-circle));
}

:host([checked]) paper-ripple {
  color: var(--cr-radio-button-checked-ripple-color);
}

</style>
  </template>
</dom-module>
  </body>
