# Hospital Registration and Appointment System (HRAS)

HRAS is an **HTML/CSS front-end prototype** exploring a hospital portal for patient registration and appointment-related services. The repository currently contains standalone webpage files.

## Prototype pages

- `homepage.html` — introductory portal page
- `welcome.html` — styled welcome page with example service categories
- `signup.html` — registration-form interface with a small client-side interaction

## Current functionality

- Displays introductory hospital-portal content.
- Presents example service categories such as appointments and patient registration.
- Shows a signup form layout.
- The signup page enables additional form fields after a NIDA number is entered.

## Important limitations

This repository is currently a front-end prototype, not a production hospital information system.

- The signup interaction only enables fields; it does **not** verify a NIDA number or retrieve official identity information.
- There is no backend, database, authentication service, or secure patient-record storage in the current files.
- Appointment booking, payments, emergency services, and medical records are presented as concepts and are not implemented as working services.
- Some navigation links refer to page filenames that are not present in the repository and need to be connected to the actual pages.

Do not enter real patient, identity, or medical information into this prototype.

## Run locally

1. Clone the repository:

   ```bash
   git clone https://github.com/eDDie-05/HRAS.git
   cd HRAS
   ```

2. Open `homepage.html` or `welcome.html` in a modern web browser.

No package installation or build step is required for the current static pages.

## Planned improvements

- Correct and test all page navigation.
- Add responsive layouts and accessible form labels.
- Design a backend API and database before implementing real registration.
- Add server-side validation and secure authentication.
- Add appointment conflict checks and role-based access controls.
- Add automated tests before treating any workflow as production-ready.

## Contributing

Open an issue to discuss a proposed improvement before submitting a pull request. Never include real patient data, identity numbers, or credentials in issues or test examples.

## License

No open-source license is currently specified. All rights remain with the respective content owner unless a license is added.
