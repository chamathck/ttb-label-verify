# ttb-label-verify
 AI-Powered Alcohol Label Verification App
TTB LabelVerify is a proof-of-concept label verification assistant designed to reduce repetitive manual comparison during alcohol beverage label review.

The application uses computer vision and OCR to extract information from uploaded label artwork and compares selected fields against application information using deterministic compliance rules.

The design prioritizes three requirements discovered during stakeholder interviews: sub-five-second interactive verification, a low-complexity user interface, and operation without dependencies on externally hosted AI APIs.

The system intentionally uses human-review states when image quality or OCR confidence prevents a reliable automated determination.
