# Pa Tong Inter Medical Clinic - wireframe prototype

A standalone, responsive source-code version of the proposed clinic wireframe.
This project is a client presentation prototype, not a production clinic system.

## Open the prototype

Open `index.html` in a modern browser. No dependencies, installation or build are required.

Alternatively, from this directory:

```sh
python3 -m http.server 8080
```

Visit http://localhost:8080 and stop the server with Ctrl+C.

## Files

- `index.html`: document, screen selector, navigation and application shell.
- `styles.css`: responsive layouts, wireframe styling and light/dark appearance.
- `app.js`: local navigation, service search, booking steps and staff demonstration.

## Included screens

1. Homepage with clinic introduction and service cards.
2. Searchable example medical service catalog.
3. Service detail with an appointment action.
4. Four-step guest appointment request and receipt.
5. Reception workspace showing a fictional request and local status changes.

The booking demo checks the required date, name, phone, contact-channel email and
appointment-terms checkbox. It keeps entered information when changing the sample
website language. Refreshing the page resets all demo state.

## Languages

Thai (`th`), English (`en`) and Burmese (`my`) are demonstrated in the global
navigation and homepage heading only. Most screen content remains English.
This is not a complete internationalization implementation. Fluent reviewers
and the clinic must approve all translations and medical terminology.

## Demonstration boundaries

- No backend, database, authentication, storage, notification delivery or payments.
- No real appointment is submitted and no slot capacity is reserved.
- The staff view uses a separate fictional record; it is not connected to booking submissions.
- Clinic details, photos, services, schedules, policies and qualifications are placeholders.
- Supporting pages named in the planning proposal are not implemented in this five-screen prototype.
- No production SEO: screen changes are local, not separate indexable service URLs.
- `noindex, nofollow` intentionally keeps this draft out of search indexes.
- Use sample data during presentations.

## Production direction

Implement approved public templates with localized, server-rendered URLs, reviewed
service content, metadata, sitemaps and language alternates. Add secure booking APIs,
clinic-configured availability, reception authentication, notification delivery and
patient request management as separate implementation work.

Before changing this prototype, confirm the full service list, appointment policy,
brand assets, translation owners and notification channels with the clinic.

## Validation

JavaScript syntax and local DOM interactions were checked: five-screen navigation,
service search, required date validation, booking progression, request receipt,
language-switch state preservation and staff confirmation validation.
The presentation PDF was visually reviewed. Full browser viewport testing of this
export was unavailable in the authoring environment; verify the layout in your
target browsers before presenting.
