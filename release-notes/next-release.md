# Release notes for cobrapy x.y.z

## New features

## Fixes

* Fixes the incorrect bounds in the CycleFree loop removal.
* Fixes reduced costs and shadow prices not available when using non-convex models.
* Fixed a bug with SBML group parsing that affects the Debian package.

## Other
* Adding a duplicate boundary reaction (with `add_boundary`) no longer errors, but instead just returns the existing reaction.

## Deprecated features

## Backwards incompatible changes
