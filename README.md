# rigthing

**https://marcuswhitfill.github.io/rigthing/**

DuckDB-wasm over `permits.zstd.parquet` plus `lod.zstd.parquet`.

Cell zoom is a precomputed XOR-folded pyramid (GF(2) `bit_xor` of well/operator hashes, stable `arg_min` representative). Pans that don't change the quantized viewport are skipped (`xor-hold`). Positions do not lerp — pins should not dance.

Open in Safari on a phone. First load ~15 MB wells + ~2.5 MB lod.

Email one-file (no parquet): `permit_atlas_mail.html` in the local pipeline folder, not this site.
