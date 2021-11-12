# About frun

frun, also known as Fake OCI Runtime, a small tool for checking gaps in CRI/container engine behavior

frun currently does not conform to the OCI Container runtime specification
(<https://github.com/opencontainers/runtime-spec>).

frun is currently written by the shell and only provides the parameters passed by the CRI to the OCI Runtime
, the environment variables, both of which may change in the future

Perhaps there are better names, such as `prun `also known as Pretend to run, `runpc` also known as run Pretend Container, etc.

# Why create frun? frun doesn't seem to be of any use at all.

Inspired by https://github.com/google/gvisor/issues/6849#issuecomment-966525492

Maybe there's a better way to do this that I don't know about
