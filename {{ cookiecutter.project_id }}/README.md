# {{ cookiecutter.project_title }}

{{ cookiecutter.project_description }}

[Project description](https://biifsweden.github.io/projects/{% now 'local', '%Y/%m/%d' %}/{{ cookiecutter.project_id }}/)

[Download code](archive/refs/heads/main.zip)

## Installation

{%- if cookiecutter.include_fiji -%}
<!-- TODO Fiji installation instructions (including version) -->
{% endif %}

{%- if cookiecutter.include_qupath -%}
<!-- TODO QuPath installation instructions (including version) -->
{% endif %}

{%- if cookiecutter.include_cellprofiler -%}
<!-- TODO CellProfiler installation instructions (including version) -->
{% endif %}

## Usage

## Cite

```
Author list ({% now 'local', '%Y' %}). Title. Zenodo. https://doi.org/... .
```

{%- if cookiecutter.include_fiji -%}
<!-- TODO Fiji citation -->
{% endif %}

{%- if cookiecutter.include_qupath -%}
<!-- TODO QuPath citation -->
{% endif %}

{%- if cookiecutter.include_cellprofiler -%}
<!-- TODO CellProfiler citation -->
{% endif %}

## License

[MIT](LICENSE)

## Contact

[SciLifeLab BioImage Informatics Facility (BIIF)](https://www.scilifelab.se/units/bioimage-informatics/)

Developed by [{{ cookiecutter.biif_developer_name }}](mailto:{{ cookiecutter.biif_developer_email }})
