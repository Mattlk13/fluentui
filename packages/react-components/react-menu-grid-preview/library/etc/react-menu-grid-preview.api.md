## API Report File for "@fluentui/react-menu-grid-preview"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

/// <reference types="react" />

import type { ComponentProps } from '@fluentui/react-utilities';
import type { ComponentState } from '@fluentui/react-utilities';
import type { ForwardRefComponent } from '@fluentui/react-utilities';
import * as React_2 from 'react';
import type { Slot } from '@fluentui/react-utilities';
import type { SlotClassNames } from '@fluentui/react-utilities';
import { TabsterDOMAttribute } from '@fluentui/react-tabster';

// @public
export const MenuGrid: ForwardRefComponent<MenuGridProps>;

// @public
export const MenuGridCell: ForwardRefComponent<MenuGridCellProps>;

// @public (undocumented)
export const menuGridCellClassNames: SlotClassNames<MenuGridCellSlots>;

// @public (undocumented)
export type MenuGridCellProps = ComponentProps<MenuGridCellSlots>;

// @public (undocumented)
export type MenuGridCellSlots = {
    root: Slot<'div'>;
};

// @public (undocumented)
export type MenuGridCellState = ComponentState<MenuGridCellSlots>;

// @public (undocumented)
export const menuGridClassNames: SlotClassNames<MenuGridSlots>;

// @public (undocumented)
export const MenuGridContextProvider: React_2.Provider<MenuGridContextValue>;

// @public
export type MenuGridContextValue = {
    tableRowTabsterAttribute: TabsterDOMAttribute | null;
};

// @public (undocumented)
export type MenuGridContextValues = {
    menuGrid: MenuGridContextValue;
};

// @public (undocumented)
export type MenuGridProps = ComponentProps<MenuGridSlots> & {};

// @public
export const MenuGridRow: ForwardRefComponent<MenuGridRowProps>;

// @public (undocumented)
export const menuGridRowClassNames: SlotClassNames<MenuGridRowSlots>;

// @public
export const MenuGridRowGroup: ForwardRefComponent<MenuGridRowGroupProps>;

// @public (undocumented)
export const menuGridRowGroupClassNames: SlotClassNames<MenuGridRowGroupSlots>;

// @public (undocumented)
export const MenuGridRowGroupContextProvider: React_2.Provider<MenuGridRowGroupContextValue>;

// @public
export type MenuGridRowGroupContextValue = {
    headerId: string;
};

// @public (undocumented)
export type MenuGridRowGroupContextValues = {
    menuGridRowGroup: MenuGridRowGroupContextValue;
};

// @public
export const MenuGridRowGroupHeader: ForwardRefComponent<MenuGridRowGroupHeaderProps>;

// @public (undocumented)
export const menuGridRowGroupHeaderClassNames: SlotClassNames<MenuGridRowGroupHeaderSlots>;

// @public (undocumented)
export type MenuGridRowGroupHeaderProps = ComponentProps<MenuGridRowGroupHeaderSlots>;

// @public (undocumented)
export type MenuGridRowGroupHeaderSlots = {
    root: Slot<'div'>;
};

// @public (undocumented)
export type MenuGridRowGroupHeaderState = ComponentState<MenuGridRowGroupHeaderSlots>;

// @public (undocumented)
export type MenuGridRowGroupProps = ComponentProps<MenuGridRowGroupSlots>;

// @public (undocumented)
export type MenuGridRowGroupSlots = {
    root: Slot<'div'>;
};

// @public (undocumented)
export type MenuGridRowGroupState = ComponentState<MenuGridRowGroupSlots> & {
    headerId: string;
};

// @public (undocumented)
export type MenuGridRowProps = ComponentProps<MenuGridRowSlots>;

// @public (undocumented)
export type MenuGridRowSlots = {
    root: Slot<'div'>;
};

// @public (undocumented)
export type MenuGridRowState = ComponentState<MenuGridRowSlots>;

// @public (undocumented)
export type MenuGridSlots = {
    root: Slot<'div'>;
};

// @public (undocumented)
export type MenuGridState = ComponentState<MenuGridSlots> & {
    tableRowTabsterAttribute: TabsterDOMAttribute | null;
};

// @public
export const renderMenuGrid_unstable: (state: MenuGridState, contextValues: MenuGridContextValues) => JSX.Element;

// @public
export const renderMenuGridCell_unstable: (state: MenuGridCellState) => JSX.Element;

// @public
export const renderMenuGridRow_unstable: (state: MenuGridRowState) => JSX.Element;

// @public
export const renderMenuGridRowGroup_unstable: (state: MenuGridRowGroupState, contextValues: MenuGridRowGroupContextValues) => JSX.Element;

// @public
export const renderMenuGridRowGroupHeader_unstable: (state: MenuGridRowGroupHeaderState) => JSX.Element;

// @public
export const useMenuGrid_unstable: (props: MenuGridProps, ref: React_2.Ref<HTMLDivElement>) => MenuGridState;

// @public
export function useMenuGridCell_unstable(props: MenuGridCellProps, ref: React_2.Ref<HTMLDivElement>): MenuGridCellState;

// @public (undocumented)
export const useMenuGridCellStyles_unstable: (state: MenuGridCellState) => MenuGridCellState;

// @public (undocumented)
export const useMenuGridContext_unstable: () => MenuGridContextValue;

// @public (undocumented)
export function useMenuGridContextValues_unstable(state: MenuGridState): MenuGridContextValues;

// @public
export function useMenuGridRow_unstable(props: MenuGridRowProps, ref: React_2.Ref<HTMLDivElement>): MenuGridRowState;

// @public
export function useMenuGridRowGroup_unstable(props: MenuGridRowGroupProps, ref: React_2.Ref<HTMLDivElement>): MenuGridRowGroupState;

// @public (undocumented)
export const useMenuGridRowGroupContext_unstable: () => MenuGridRowGroupContextValue;

// @public (undocumented)
export function useMenuGridRowGroupContextValues_unstable(state: MenuGridRowGroupState): MenuGridRowGroupContextValues;

// @public
export function useMenuGridRowGroupHeader_unstable(props: MenuGridRowGroupHeaderProps, ref: React_2.Ref<HTMLDivElement>): MenuGridRowGroupHeaderState;

// @public (undocumented)
export const useMenuGridRowGroupHeaderStyles_unstable: (state: MenuGridRowGroupHeaderState) => MenuGridRowGroupHeaderState;

// @public (undocumented)
export const useMenuGridRowGroupStyles_unstable: (state: MenuGridRowGroupState) => MenuGridRowGroupState;

// @public (undocumented)
export const useMenuGridRowStyles_unstable: (state: MenuGridRowState) => MenuGridRowState;

// @public
export const useMenuGridStyles_unstable: (state: MenuGridState) => MenuGridState;

// (No @packageDocumentation comment for this package)

```
