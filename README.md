# Protobuf WKT

Mirror of the [`google.protobuf`](https://developers.google.com/protocol-buffers/docs/reference/google.protobuf)
package containing the well-known types only, in contrast to the
[original repository](https://github.com/protocolbuffers/protobuf) that contains
all sorts of other stuff.

I created this repository because I wanted to have a single convenient source to
retrieve the well-known types and only the well-known types. This repository
is backed by a scheduled workflow that synchronizes the branches and releases of
this repository with the upstream on a daily basis; filtering out any unwanted
contents.

There is a branch for every Protobuf release as well as a tag and a GitHub
release. They contain the WKT Protobuf definitions and the original license
only, nothing else!

## License

The content of this branch is licensed under the [Unlicense](UNLICENSE).
Other branches have their own license, please refer to the individual `LICENSE`
files of them.
