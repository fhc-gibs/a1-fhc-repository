# A1/FHC Project Repository — Source File Archive
Crawled from NewRoof CRM on 2026-11-24. 721 of 737 referenced files downloaded successfully (97.9%).

## Folder structure
One folder per project, with files organized into the same document categories NewRoof uses
(contract, proposal, insuranceBonding, submittals, approvedSubmittals, plansSpecs, drawings,
photosReports, permits, invoices, changeOrderRequests, etc.)

- Achieve_Financial/      (22 files - Achieve Financial Credit Union, New Britain CT)
- Berlin-Peck_Library/    (84 files - Berlin-Peck Memorial Library Reroofing, Berlin CT)
- Betty_Knox_Apartments/  (48 files - Betty Knox Apartments, RFP #1287, Hartford CT)
- CHCH_Fort_Oglethorpe/   (42 files - Chickamauga & Chattanooga NMP Maintenance Complex, GA)
- Cape_Cod_Canal/         (46 files - Cape Cod Canal Administration Building, Bourne MA)
- Fort_Buchanan_PR/       (139 files - Fort Buchanan IDIQ, Puerto Rico)
- Groton_Library/         (36 files - Town of Groton Public Library, Groton CT)
- NVCC/                   (57 files - Naugatuck Valley Community College Small Roofs)
- Real_Art_Ways/          (145 files - Real Art Ways Renovation & Expansion, Hartford CT)
- UConn_Drama/            (54 files - UConn Drama Music Building, Mansfield CT)
- UConn_Gampel_Pavilion/  (64 files - UConn Gampel Pavilion Renovation, Mansfield CT)

## 16 files that could not be retrieved (source-side, not fixable from here)
10 files are on old res.cloudinary.com links with expired/revoked signed-URL tokens
(HTTP 401 Unauthorized at the CDN) — these were superseded by newer CloudFront copies
of the same documents in most cases:
  - Cape_Cod_Canal: "2-5-26 - PreConstruct Meeting.pdf" (Scheduled Meetings)
  - Fort_Buchanan_PR: Attachment 1-6 bid documents + the FY23 roofing drawing (7 files,
    "bidDocuments"/"architectDrawings") — NOTE: these look like original solicitation
    attachments that may not exist elsewhere in the job; worth asking NewRoof admin to
    re-upload if needed.
  - NVCC: 6 contract-folder files (Bid Proposal, A201-2017 General Conditions, Addendum
    ONE, AIA A101-2017, Invitation to Bid, Project Manual) — all from the original Nov
    2025 bid package.

1 file returned HTTP 403 Forbidden (Access Denied) directly from the live CloudFront CDN,
unlike every other file in this archive, meaning its underlying storage object itself
appears to be missing or restricted — not a link-rot issue:
  - UConn_Gampel_Pavilion: "#074100-002-0 Canopy Roofing Product Data.pdf" (submittals)

All other files in the "Approved Subcontractors / Approved Submittals / Approved Products"
repository doc are present in this archive under their project's "approvedSubmittals",
"insuranceBonding", "contract", or "submittals" folder.
