# Changelog

## 5.4.0

- Feature: Adding ability to have custom width and height per each node. (#148)

## 5.3.0

- Feature: Adds zoomChange output (#141)
- Feature: Adds dagre layout options input (#146)
- Enhancement: Calculates biggest bounding box of tall text fields in node (#84)
- Bug: Fixes issue not being able to zoom if the current zoom goes out of the min/max zoom range (#146)

## 5.2.1

- Fix: Restore the HTML content inside the component (#140)

## 5.2.0

- Add new user template in order to show UI data on the link (#138)
- Feature: Adds zoom to node functionality (#133)
- Bug: Fixes panning to a location and centering the graph

## 5.1.2

- Chore: Update dependencies

## 5.1.1

- Bug: TouchEvent not defined in dev mode for non-Chrome browsers (#99)

## 5.1.0

- Feature: Allow panning on touch events (#86)
- Bug: Fix panning speed (#88)

## 5.0.1

- Chore: Update dagre version

## 5.0.0

- Chore: Upgrade to Angular 6

## 4.3.0

- Feature: Add update$, center$, and zoomToFit\$ inputs

## 4.2.0

- Feature: Add autoCenter and autoZoom inputs (#51)

## 4.1.0

- Feature: Allow enable/disable zooming (#64)
- Feature: Pan to cursor on zoom (#53)
- Docs: Use ng-template instead of template (#48)

## 4.0.2

- Fix: Error in Firefox when trying to render diagram when it is hidden

## 4.0.1

- Fix: Fix build for AOT projects.

## 4.0.0

- Breaking: Renamed the npm package to `@swimlane/ngx-graph`
- Breaking: Renamed the module to `NgxGraph`
- Breaking: Renamed the component selector to `ngx-graph`
- Docs: Updated readme