python_sources(
    name="root",
)

pex_binary(
    name="main",
    entry_point="main.py",
    dependencies=["//main.py:root"],
    complete_platforms=[":linux_x86_py38"],
)

file(
    name="linux_x86_py38",
    source="linux_x86_py38.json",
)
