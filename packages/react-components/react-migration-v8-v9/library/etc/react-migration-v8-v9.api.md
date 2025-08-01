## API Report File for "@fluentui/react-migration-v8-v9"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { BrandVariants } from '@fluentui/react-components';
import type { ButtonProps } from '@fluentui/react-components';
import type { IBaseButtonProps } from '@fluentui/react';
import type { IButtonProps } from '@fluentui/react';
import { ICheckboxProps } from '@fluentui/react';
import type { IContextualMenuItem } from '@fluentui/react';
import type { IContextualMenuProps } from '@fluentui/react';
import type { IPalette } from '@fluentui/react';
import type { IStackItemProps } from '@fluentui/react';
import type { IStackProps } from '@fluentui/react';
import type { JSXElement } from '@fluentui/react-utilities';
import type { MenuProps } from '@fluentui/react-components';
import * as React_2 from 'react';
import { Theme } from '@fluentui/react-components';
import { Theme as Theme_2 } from '@fluentui/react';

// @public
const ActionButtonShim: React_2.ForwardRefExoticComponent<IButtonProps & React_2.RefAttributes<HTMLButtonElement>>;
export { ActionButtonShim }
export { ActionButtonShim as CommandButtonShim }

// @public (undocumented)
export type AlphaColors = 5 | 10 | 20 | 30 | 40 | 50 | 60 | 70 | 80 | 90;

// @public (undocumented)
export const black = "#000000";

// @public (undocumented)
export const blackAlpha: Record<AlphaColors, string>;

// @public (undocumented)
export const brandWeb: BrandVariants;

// @public (undocumented)
export const ButtonShim: React_2.ForwardRefExoticComponent<IBaseButtonProps & React_2.RefAttributes<HTMLButtonElement>>;

// @public (undocumented)
export const CheckboxShim: React_2.ForwardRefExoticComponent<ICheckboxProps & React_2.RefAttributes<HTMLInputElement>>;

// @public
export type ColorVariants = {
    shade50: string;
    shade40: string;
    shade30: string;
    shade20: string;
    shade10: string;
    primary: string;
    tint10: string;
    tint20: string;
    tint30: string;
    tint40: string;
    tint50: string;
    tint60: string;
};

// @public
export const CompoundButtonShim: React_2.ForwardRefExoticComponent<IButtonProps & React_2.RefAttributes<HTMLButtonElement>>;

// @public
export const createBrandVariants: (palette: IPalette, interpolation?: Interpolation) => BrandVariants;

// @public
export const createV8Theme: (brandColors: BrandVariants, themeV9: Theme, isDarkTheme?: boolean, themeV8?: Theme_2) => Theme_2;

// @public
export const createV9Theme: (themeV8: Theme_2, baseThemeV9?: Theme) => Theme;

// @public
export const DefaultButtonShim: React_2.ForwardRefExoticComponent<IButtonProps & React_2.RefAttributes<HTMLButtonElement>>;

// @public
export type GlobalSharedColors = {
    darkRed: ColorVariants;
    burgundy: ColorVariants;
    cranberry: ColorVariants;
    red: ColorVariants;
    darkOrange: ColorVariants;
    bronze: ColorVariants;
    pumpkin: ColorVariants;
    orange: ColorVariants;
    peach: ColorVariants;
    marigold: ColorVariants;
    yellow: ColorVariants;
    gold: ColorVariants;
    brass: ColorVariants;
    brown: ColorVariants;
    darkBrown: ColorVariants;
    lime: ColorVariants;
    forest: ColorVariants;
    seafoam: ColorVariants;
    lightGreen: ColorVariants;
    green: ColorVariants;
    darkGreen: ColorVariants;
    lightTeal: ColorVariants;
    teal: ColorVariants;
    darkTeal: ColorVariants;
    cyan: ColorVariants;
    steel: ColorVariants;
    lightBlue: ColorVariants;
    blue: ColorVariants;
    royalBlue: ColorVariants;
    darkBlue: ColorVariants;
    cornflower: ColorVariants;
    navy: ColorVariants;
    lavender: ColorVariants;
    purple: ColorVariants;
    darkPurple: ColorVariants;
    orchid: ColorVariants;
    grape: ColorVariants;
    berry: ColorVariants;
    lilac: ColorVariants;
    pink: ColorVariants;
    hotPink: ColorVariants;
    magenta: ColorVariants;
    plum: ColorVariants;
    beige: ColorVariants;
    mink: ColorVariants;
    silver: ColorVariants;
    platinum: ColorVariants;
    anchor: ColorVariants;
    charcoal: ColorVariants;
};

// @public (undocumented)
export const grey: Record<Greys, string>;

// @public (undocumented)
export const grey14Alpha: Record<AlphaColors, string>;

// @public (undocumented)
export type Greys = 0 | 2 | 4 | 6 | 8 | 10 | 12 | 14 | 16 | 18 | 20 | 22 | 24 | 26 | 28 | 30 | 32 | 34 | 36 | 38 | 40 | 42 | 44 | 46 | 48 | 50 | 52 | 54 | 56 | 58 | 60 | 62 | 64 | 66 | 68 | 70 | 72 | 74 | 76 | 78 | 80 | 82 | 84 | 86 | 88 | 90 | 92 | 94 | 96 | 98 | 100;

// @public (undocumented)
export const hcButtonFace = "#ffffff";

// @public (undocumented)
export const hcButtonText = "#000000";

// @public (undocumented)
export const hcCanvas = "#000000";

// @public (undocumented)
export const hcCanvasText = "#ffffff";

// @public (undocumented)
export const hcDisabled = "#3ff23f";

// @public (undocumented)
export const hcHighlight = "#1aebff";

// @public (undocumented)
export const hcHighlightText = "#000000";

// @public (undocumented)
export const hcHyperlink = "#ffff00";

// @public (undocumented)
export const MenuButtonShim: React_2.ForwardRefExoticComponent<IButtonProps & React_2.RefAttributes<HTMLButtonElement>>;

// @public (undocumented)
export const MenuItemShim: (props: IContextualMenuItem) => JSXElement;

// @public
export const PrimaryButtonShim: React_2.ForwardRefExoticComponent<IButtonProps & React_2.RefAttributes<HTMLButtonElement>>;

// @public (undocumented)
export const sharedColors: GlobalSharedColors;

// @public (undocumented)
export const shimButtonProps: (props: IBaseButtonProps & React_2.RefAttributes<HTMLButtonElement>) => ButtonProps;

// @public (undocumented)
export const shimMenuProps: (props: IContextualMenuProps) => Partial<MenuProps>;

// @public (undocumented)
export const StackItemShim: (props: IStackItemProps) => JSXElement;

// @public (undocumented)
export const StackShim: (props: IStackProps) => JSXElement;

// @public (undocumented)
export type TextAlignment = 'inherit' | 'initial' | 'revert' | 'unset' | 'center' | 'end' | 'start' | 'justify' | 'left' | 'match-parent' | 'right';

// @public (undocumented)
export type TextAlignments = {
    start: TextAlignment;
    center: TextAlignment;
    end: TextAlignment;
    justify: TextAlignment;
};

// @public
export const ToggleButtonShim: React_2.ForwardRefExoticComponent<IButtonProps & React_2.RefAttributes<HTMLButtonElement>>;

// @public (undocumented)
export const white = "#ffffff";

// @public (undocumented)
export const whiteAlpha: Record<AlphaColors, string>;

// (No @packageDocumentation comment for this package)

```
