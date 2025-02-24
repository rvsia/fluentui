## API Report File for "@fluentui/react-badge"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import type { ComponentProps } from '@fluentui/react-utilities';
import type { ComponentState } from '@fluentui/react-utilities';
import { ObjectShorthandProps } from '@fluentui/react-utilities';
import * as React_2 from 'react';
import { ShorthandProps } from '@fluentui/react-utilities';
import { ShorthandRenderFunction } from '@fluentui/react-utilities';

// @public
export const Badge: React_2.ForwardRefExoticComponent<Pick<{
    root?: ShorthandProps<ObjectShorthandProps<React_2.HTMLAttributes<HTMLElement>>>;
    icon?: ShorthandProps<ObjectShorthandProps<React_2.HTMLAttributes<HTMLElement>>>;
}, "icon"> & React_2.HTMLAttributes<HTMLElement> & {
    children?: string | number | boolean | {} | React_2.ReactElement<any, string | ((props: any) => React_2.ReactElement<any, string | any | (new (props: any) => React_2.Component<any, any, any>)> | null) | (new (props: any) => React_2.Component<any, any, any>)> | React_2.ReactNodeArray | React_2.ReactPortal | ShorthandRenderFunction<React_2.HTMLAttributes<HTMLElement>> | null | undefined;
} & Partial<BadgeCommons> & React_2.RefAttributes<HTMLElement>>;

// @public (undocumented)
export type BadgeCommons = {
    appearance: 'filled' | 'ghost' | 'outline' | 'tint';
    color: 'brand' | 'danger' | 'important' | 'informative' | 'severe' | 'subtle' | 'success' | 'warning';
    iconPosition: 'before' | 'after';
    shape: 'circular' | 'rounded' | 'square';
    size: 'tiny' | 'extra-small' | 'small' | 'medium' | 'large' | 'extra-large';
};

// @public (undocumented)
export type BadgeProps = ComponentProps<Partial<BadgeSlots>> & Partial<BadgeCommons>;

// @public (undocumented)
export type BadgeSlots = {
    root: ObjectShorthandProps<React_2.HTMLAttributes<HTMLElement>>;
    icon?: ObjectShorthandProps<React_2.HTMLAttributes<HTMLElement>>;
};

// @public (undocumented)
export type BadgeState = ComponentState<BadgeSlots> & BadgeCommons;

// @public
export const CounterBadge: React_2.ForwardRefExoticComponent<Pick<BadgeProps, "icon" | "children" | "defaultChecked" | "defaultValue" | "suppressContentEditableWarning" | "suppressHydrationWarning" | "accessKey" | "className" | "contentEditable" | "contextMenu" | "dir" | "draggable" | "hidden" | "id" | "lang" | "placeholder" | "slot" | "spellCheck" | "style" | "tabIndex" | "title" | "translate" | "radioGroup" | "role" | "about" | "datatype" | "inlist" | "prefix" | "property" | "resource" | "typeof" | "vocab" | "autoCapitalize" | "autoCorrect" | "autoSave" | "color" | "itemProp" | "itemScope" | "itemType" | "itemID" | "itemRef" | "results" | "security" | "unselectable" | "inputMode" | "is" | "aria-activedescendant" | "aria-atomic" | "aria-autocomplete" | "aria-busy" | "aria-checked" | "aria-colcount" | "aria-colindex" | "aria-colspan" | "aria-controls" | "aria-current" | "aria-describedby" | "aria-details" | "aria-disabled" | "aria-dropeffect" | "aria-errormessage" | "aria-expanded" | "aria-flowto" | "aria-grabbed" | "aria-haspopup" | "aria-hidden" | "aria-invalid" | "aria-keyshortcuts" | "aria-label" | "aria-labelledby" | "aria-level" | "aria-live" | "aria-modal" | "aria-multiline" | "aria-multiselectable" | "aria-orientation" | "aria-owns" | "aria-placeholder" | "aria-posinset" | "aria-pressed" | "aria-readonly" | "aria-relevant" | "aria-required" | "aria-roledescription" | "aria-rowcount" | "aria-rowindex" | "aria-rowspan" | "aria-selected" | "aria-setsize" | "aria-sort" | "aria-valuemax" | "aria-valuemin" | "aria-valuenow" | "aria-valuetext" | "dangerouslySetInnerHTML" | "onCopy" | "onCopyCapture" | "onCut" | "onCutCapture" | "onPaste" | "onPasteCapture" | "onCompositionEnd" | "onCompositionEndCapture" | "onCompositionStart" | "onCompositionStartCapture" | "onCompositionUpdate" | "onCompositionUpdateCapture" | "onFocus" | "onFocusCapture" | "onBlur" | "onBlurCapture" | "onChange" | "onChangeCapture" | "onBeforeInput" | "onBeforeInputCapture" | "onInput" | "onInputCapture" | "onReset" | "onResetCapture" | "onSubmit" | "onSubmitCapture" | "onInvalid" | "onInvalidCapture" | "onLoad" | "onLoadCapture" | "onError" | "onErrorCapture" | "onKeyDown" | "onKeyDownCapture" | "onKeyPress" | "onKeyPressCapture" | "onKeyUp" | "onKeyUpCapture" | "onAbort" | "onAbortCapture" | "onCanPlay" | "onCanPlayCapture" | "onCanPlayThrough" | "onCanPlayThroughCapture" | "onDurationChange" | "onDurationChangeCapture" | "onEmptied" | "onEmptiedCapture" | "onEncrypted" | "onEncryptedCapture" | "onEnded" | "onEndedCapture" | "onLoadedData" | "onLoadedDataCapture" | "onLoadedMetadata" | "onLoadedMetadataCapture" | "onLoadStart" | "onLoadStartCapture" | "onPause" | "onPauseCapture" | "onPlay" | "onPlayCapture" | "onPlaying" | "onPlayingCapture" | "onProgress" | "onProgressCapture" | "onRateChange" | "onRateChangeCapture" | "onSeeked" | "onSeekedCapture" | "onSeeking" | "onSeekingCapture" | "onStalled" | "onStalledCapture" | "onSuspend" | "onSuspendCapture" | "onTimeUpdate" | "onTimeUpdateCapture" | "onVolumeChange" | "onVolumeChangeCapture" | "onWaiting" | "onWaitingCapture" | "onAuxClick" | "onAuxClickCapture" | "onClick" | "onClickCapture" | "onContextMenu" | "onContextMenuCapture" | "onDoubleClick" | "onDoubleClickCapture" | "onDrag" | "onDragCapture" | "onDragEnd" | "onDragEndCapture" | "onDragEnter" | "onDragEnterCapture" | "onDragExit" | "onDragExitCapture" | "onDragLeave" | "onDragLeaveCapture" | "onDragOver" | "onDragOverCapture" | "onDragStart" | "onDragStartCapture" | "onDrop" | "onDropCapture" | "onMouseDown" | "onMouseDownCapture" | "onMouseEnter" | "onMouseLeave" | "onMouseMove" | "onMouseMoveCapture" | "onMouseOut" | "onMouseOutCapture" | "onMouseOver" | "onMouseOverCapture" | "onMouseUp" | "onMouseUpCapture" | "onSelect" | "onSelectCapture" | "onTouchCancel" | "onTouchCancelCapture" | "onTouchEnd" | "onTouchEndCapture" | "onTouchMove" | "onTouchMoveCapture" | "onTouchStart" | "onTouchStartCapture" | "onPointerDown" | "onPointerDownCapture" | "onPointerMove" | "onPointerMoveCapture" | "onPointerUp" | "onPointerUpCapture" | "onPointerCancel" | "onPointerCancelCapture" | "onPointerEnter" | "onPointerEnterCapture" | "onPointerLeave" | "onPointerLeaveCapture" | "onPointerOver" | "onPointerOverCapture" | "onPointerOut" | "onPointerOutCapture" | "onGotPointerCapture" | "onGotPointerCaptureCapture" | "onLostPointerCapture" | "onLostPointerCaptureCapture" | "onScroll" | "onScrollCapture" | "onWheel" | "onWheelCapture" | "onAnimationStart" | "onAnimationStartCapture" | "onAnimationEnd" | "onAnimationEndCapture" | "onAnimationIteration" | "onAnimationIterationCapture" | "onTransitionEnd" | "onTransitionEndCapture" | "css" | "iconPosition" | "size"> & Partial<CounterBadgeCommons> & React_2.RefAttributes<HTMLElement>>;

// @public (undocumented)
export type CounterBadgeCommons = {
    overflowCount: number;
    count: number;
    showZero: boolean;
    dot: boolean;
    shape: 'circular' | 'rounded';
    appearance: 'filled' | 'ghost';
};

// @public (undocumented)
export type CounterBadgeProps = Omit<BadgeProps, 'appearance' | 'shape'> & Partial<CounterBadgeCommons>;

// @public (undocumented)
export type CounterBadgeState = Omit<BadgeState, 'appearance' | 'shape'> & CounterBadgeCommons;

// @public
export const PresenceBadge: React_2.ForwardRefExoticComponent<Pick<{
    root?: ShorthandProps<ObjectShorthandProps<React_2.HTMLAttributes<HTMLElement>>>;
    icon?: ShorthandProps<ObjectShorthandProps<React_2.HTMLAttributes<HTMLElement>>>;
}, "icon"> & React_2.HTMLAttributes<HTMLElement> & {
    children?: string | number | boolean | {} | React_2.ReactElement<any, string | ((props: any) => React_2.ReactElement<any, string | any | (new (props: any) => React_2.Component<any, any, any>)> | null) | (new (props: any) => React_2.Component<any, any, any>)> | React_2.ReactNodeArray | React_2.ReactPortal | ShorthandRenderFunction<React_2.HTMLAttributes<HTMLElement>> | null | undefined;
} & Partial<BadgeCommons> & Partial<PresenceBadgeCommons> & React_2.RefAttributes<HTMLElement>>;

// @public (undocumented)
export interface PresenceBadgeCommons {
    outOfOffice: boolean;
    status: PresenceBadgeStatus;
}

// @public (undocumented)
export type PresenceBadgeProps = BadgeProps & Partial<PresenceBadgeCommons>;

// @public (undocumented)
export type PresenceBadgeState = BadgeState & PresenceBadgeCommons;

// @public (undocumented)
export type PresenceBadgeStatus = 'busy' | 'outOfOffice' | 'away' | 'available' | 'offline' | 'doNotDisturb';

// @public (undocumented)
export const renderBadge: (state: BadgeState) => JSX.Element;

// @public
export const useBadge: (props: BadgeProps, ref: React_2.Ref<HTMLElement>) => BadgeState;

// @public
export const useBadgeStyles: (state: BadgeState) => BadgeState;

// @public
export const useCounterBadge: (props: CounterBadgeProps, ref: React_2.Ref<HTMLElement>) => CounterBadgeState;

// @public
export const useCounterBadgeStyles: (state: CounterBadgeState) => CounterBadgeState;

// @public
export const usePresenceBadge: (props: PresenceBadgeProps, ref: React_2.Ref<HTMLElement>) => PresenceBadgeState;

// @public
export const usePresenceBadgeStyles: (state: PresenceBadgeState) => PresenceBadgeState;

// (No @packageDocumentation comment for this package)

```
