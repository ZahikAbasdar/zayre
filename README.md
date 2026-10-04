# ZAYRÉ

**FROM KASHMIR, WITH SOUL.**

ZAYRÉ is being built as a premium commerce and discovery experience for carefully sourced products from Kashmir. Trust, honest product information, and verified provenance are foundational principles.

## Project status

This repository has just been created. No mobile app, API, database, payments, authentication, or admin system is implemented yet. The first engineering step is to inspect and document the foundation before building features; planned capabilities are not available functionality.

## Planned direction

- **Mobile:** Flutter and Dart for iOS and Android.
- **API:** Python, FastAPI, Pydantic, and SQLAlchemy.
- **Data:** PostgreSQL, with Redis only where justified.
- **Operations:** local Docker Compose and configurable deployment.

These are proposed technologies from the product brief, not yet validated against existing project code. Architecture decisions will be recorded as they are verified.

## Product principles

- Never fabricate stock, origin, reviews, certification, delivery estimates, payment results, or tracking.
- Keep pricing, inventory, authorization, and payment verification on trusted server-side boundaries.
- Build a smaller real customer journey instead of presenting unimplemented screens as working features.
- Keep secrets out of source control.

## Development

There is no runnable application or test suite yet. Setup and validation commands will be documented when the corresponding components exist.
