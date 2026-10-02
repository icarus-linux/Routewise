# Routewise

A browser-based platform for companies to track vehicles, operational information, and company activity in a simple, modern, and affordable way.

Routewise is being developed as a practical learning project with long-term potential for real-world use, monetization, and open-source community growth. The platform is intended to be hosted locally unless otherwise stated, allowing businesses to connect to it in a controlled environment.

## Overview

Routewise aims to give businesses a clear view of daily fleet operations. The current project is an early static HTML prototype: its pages outline general-user and company-admin workflows, but do not yet provide authentication, persistence, live tracking, or payments.

The planned product is designed to support:

- Vehicle and fleet tracking
- Company-level operational visibility
- General-user route and issue workflows
- Company-admin user management and token purchasing
- Company settings and activity history

## Why Routewise

This project is built around a few core principles:

- Keep costs low while still delivering value
- Maintain a modern and minimal user experience
- Make operations easier to monitor from the browser
- Provide practical admin tools for company staff
- Support growth through documentation, communication, and refinement

## Current Prototype

- Browser-openable HTML pages in `src/`
- General-user page placeholders in `src/generaluser/`
- Company-admin page placeholders in `src/Admin/`
- HTML table navigation at the top of each role page, linking only to pages in that role's folder
- Shared responsive styling in `src/styles/styles.css`, using the Routewise navy-and-teal brand palette
- Routewise logo marks in page headers and active-page indicators in role navigation
- Dashboard overview sections arranged as a responsive tile grid
- Static tables and text placeholders for planned workflows; create and report pages are not interactive forms

To preview the prototype, open `src/index.html` in a browser. The stylesheet and logo use relative paths, so keep the repository folder structure intact. The admin dashboard can also be opened directly at `src/Admin/admin_dashboard.html`.

The login link currently opens the general-user dashboard without validating credentials. Tables are not connected to a data source, and role-specific navigation does not provide access control. Company-admin pages are not protected by authentication or role checks.

The current pricing concept is to provide new companies with 10 free credits before paid access is required. Token balances and purchases are not implemented yet.

## Project Goals

The project is intended to balance usefulness, affordability, and clarity:

- Help companies track essential operational information
- Keep the platform easy to understand and operate
- Make support and communication straightforward
- Document project progress clearly for contributors and forks
- Create a reliable foundation for future growth and functionality

## Support and Communication

Support is part of the product direction. Planned support options include AI assistance, live support, clear communication channels, and public documentation. These services are not part of the current static prototype. Project updates are shared through the YouTube channel.

## Contact

- Email: routewise.temp@proton.me
- YouTube: https://www.youtube.com/@icarus-svg

## Project Updates

Progress, walkthroughs, and public updates will be shared on the project YouTube channel:

- https://www.youtube.com/@icarus-svg

## Project Structure

The repository is organized to keep the root clean and easy to navigate:

- readme.md stays in the main project folder as the primary entry point.
- src/index.html is the demo login page.
- src/generaluser/ contains general-user pages for dashboards, fleet, routes, issues, logs, and token activity.
- src/Admin/ contains company-admin pages for the admin dashboard, user management, token management, activity, and settings.
- src/styles/ contains the shared stylesheet.
- assets/ stores branding and image resources, including the Routewise logo kit.
- docs/ contains the project documentation, user guides, and troubleshooting files.
- docs/guides/ contains the user guide and troubleshooting guide.

This keeps the main folder focused and helps contributors find documentation and assets without cluttering the project root.

Any time a new project folder is added, this section should be updated so the README continues to reflect the structure accurately.

## Notes

Routewise is positioned as an approachable, adaptable, and practical project intended to grow through use, documentation, and gradual improvement. It is meant to be useful for businesses while remaining flexible enough to support future development and broader adoption.

## Status

This repository is currently a project foundation with static page prototypes and documentation. Backend storage, real authentication, role enforcement, live fleet data, and token payments remain future work.
