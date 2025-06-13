# DNS Lookup by Internet Design Wizard

A simple, client-side web application for performing DNS lookups and exporting the results.

## Features

- Enumerates subdomains via \[crt.sh]
- Resolves DNS records (A, AAAA, CNAME, MX, TXT, NS, SRV, CAA, SOA)
- Dynamic filtering, grouping, and sorting with DataTables
- Download results as CSV, TXT, or PDF (with header/footer)
- Shareable via URL parameter: `?domain=example.com`

## Demo

Live on GitHub Pages: [https://checkdns.idw.agency](https://checkdns.idw.agency)

## Installation

No build step required—just host the static files. To develop locally:

```bash
# Clone the repo
git clone https://github.com/internetdesignwizard/DNS-Lookup.git
cd DNS-Lookup
# Open index.html in your browser (or serve via any static server)
```

## Usage

1. Enter a domain and click **Lookup**
2. Filter, sort, or search the results in real time
3. Click **Download PDF/CSV/TXT** to export

## Contributing

Contributions are welcome! To ensure project integrity:

- **Signed Commits**: All commits must be GPG-signed and verified. Unsigned commits will be rejected.
- **Branch Protection**: Only IDW-authorized personnel may push directly to the `main` branch. All others should open pull requests against `main`.
- **Pull Requests**: Submit changes via pull request. Include a clear description of the problem and your solution.
- **Code of Conduct**: Please review the [Code of Conduct](CODE_OF_CONDUCT.md) before contributing.

## License

This project is licensed under the [MIT License](LICENSE.md).
--END--
