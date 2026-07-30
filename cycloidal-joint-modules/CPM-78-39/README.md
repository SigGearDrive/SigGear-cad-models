# CPM-78-39 CAD Resources

## Product

CPM-78-39 integrated cycloidal joint module.

For product specifications, application information and controlled technical data, refer to the official product documentation:

https://siggeardrive.github.io/SigGear-product-docs/products/cycloidal-joint-modules/cpm78-39/

## CAD Directory Structure

```text
CPM-78-39/
├── README.md
├── STEP/
│   └── Place STEP files here
├── Preview/
│   ├── preview_iso.png
│   ├── preview_side.png
│   └── preview_mounting.png
└── Version/
    ├── CHANGELOG.md
    └── release-info.yml
```

## Available Files

| File type | Description |
| --- | --- |
| STEP | 3D mechanical model for integration and fit checking |
| Preview images | Visual reference before CAD download |
| Release notes | CAD revision and release-status information |

## CAD Usage Notes

Public CAD files are intended for mechanical layout, envelope checking, prototype integration and early-stage design review.

Before final mechanical design release, confirm the product configuration, mounting interface, shaft and flange dimensions, cable and connector arrangement, tolerance requirements and final revision status with SigGear.

## File Naming

Use:

```text
SigGear_CPM-78-39_<assembly-or-part>_v<revision>.step
```

Recommended preview names:

```text
preview_iso.png
preview_side.png
preview_mounting.png
```

## CAD Release Checklist

Before publishing CAD files:

- Confirm the exact product model and configuration.
- Confirm that the model uses millimetres.
- Open and inspect the exported STEP file.
- Remove confidential customer information and restricted geometry.
- Use the approved filename and CAD revision.
- Add preview images.
- Update `Version/CHANGELOG.md`.
- Update `Version/release-info.yml`.
- Confirm that README, filenames and version metadata agree.

## Current Release Status

No public CAD file is released from this directory until `Version/release-info.yml` is changed from `template_only` to `released` and an actual STEP file is present.

## Request Additional Files

For detailed drawings, missing CAD formats, customized interfaces, samples or quotation support:

https://siggeardrive.github.io/SigGear-product-docs/request-cad-sample-quote/

Email: wangwanrong@siggear.com
