# test-downstream-data

RNA-seq test data for downstream analysis pipeline validation. Contains samplesheets and count matrices for testing differential expression analysis modules.

## Current Contents

### RNA-seq Test Datasets:
1. **Plant Pathogen Timecourse** (`samplesheet_plant_timecourse.csv`)
   - 48 samples: MLA1 vs triple mutant plants
   - 4 timepoints (6, 12, 18, 24 hpi)
   - 3 replicates per condition
   - Count matrix: `plant_timecourse_raw_counts.rds`

2. **Leishmaniasis Clinical Study** (`samplesheet_leishmaniasis.csv`)
   - Patients vs healthy controls
   - Clinical metadata included
   - Count matrix: `leishmaniasis_raw_counts.rds`

## Usage

Use with nf-core RNA-seq pipelines for testing downstream analysis modules.

## License

MIT License
