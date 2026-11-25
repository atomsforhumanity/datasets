# Atoms for Humanity datasets

**Let's build the chemistry datasets the field needs, together, and give them away.**

[Atoms for Humanity](https://afh.org) runs quantum chemistry at scale on a large pool of CPUs and data center
GPUs, with open codes we build and test carefully. We want to make open datasets together with the people who
will use them: you bring the scientific question, the chemistry you know, structures or a method to put to the
test; we bring the compute, the codes and the engineering to run it at scale and document every record. The best
datasets come from that kind of partnership, and this repository is where it starts.

There are many ways in:

- **Propose a dataset** you wish existed, even as a rough idea.
- **Design one with us**: the chemical space, the level of theory, the properties, the checks.
- **Bring the chemistry**: structures, a hard benchmark, a workflow you want run at scale.
- **Test and use it**: validate early releases against your methods and tell us what's missing.
- **Analyse and publish together**: substantial collaborations can lead to joint papers.

Everything we compute here is released openly under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/),
with its full provenance, so anyone can use it, cite it and build on it.

## How to take part

| You want to... | Do this |
|---|---|
| **Propose a dataset** | Open a [dataset request](https://github.com/atomsforhumanity/datasets/discussions/new?category=ideas). The form asks for what we need to scope it; "I'm not sure" is a fine answer to most questions. |
| **Support someone else's idea** | Add a 👍 to the request and a comment on how you would use it. Requests with more support move up. |
| **Ask a question** | Start a thread in [Q&A](https://github.com/atomsforhumanity/datasets/discussions/categories/q-a). |
| **Talk to us privately** | Email **datasets@afh.org**, for example if your plans aren't public yet. |
| **Report a problem with a released dataset** | Open an [issue](https://github.com/atomsforhumanity/datasets/issues/new/choose). |
| **See what's been released** | [DATASETS.md](DATASETS.md) and the [Announcements](https://github.com/atomsforhumanity/datasets/discussions/categories/announcements). |

## What we can compute

- **Density functional theory and Hartree–Fock** with [linus](https://github.com/atomsforhumanity/linus), our
  open-source, GPU-accelerated code (`pip install afh-linus`): energies, analytic gradients and Hessians, vibrational
  frequencies and IR intensities, dipoles and polarizabilities, implicit solvent (C-PCM), closed and open
  shells, from small molecules to systems of several hundred atoms.
- **Semiempirical tight binding** with [axtb](https://github.com/atomsforhumanity/axtb), our open-source
  extended tight-binding code (GFN2-xTB, g-xTB, GFN-FF; `pip install axtb`): fast energies, forces,
  frequencies and geometries for large numbers of structures.
- **Other established codes** where their licences allow the results to be published: for example conformer
  ensembles (CREST), geometry optimizations, transition states and reaction paths.
- **Structured results** in [AFH qcdata](https://github.com/atomsforhumanity/qcdata), our open data model
  for quantum chemistry inputs and outputs, or in the format your tools need.
- **At scale:** thousands to millions of calculations, with the settings, program versions and hardware of
  every record kept.

Not sure whether something is possible? Ask. Part of the point of this repository is to find out together.

## What happens to a request

1. **Proposed.** You open a request; anyone can comment and add support.
2. **Under review.** We scope it with you: chemical space, level of theory, size, cost, and how it will be used.
3. **Planned.** We commit to computing it and say roughly when.
4. **Computing.** Progress updates go in the request's thread.
5. **Released.** The dataset is published with a README, its provenance and a citable record, announced here,
   and linked from the request and from [DATASETS.md](DATASETS.md).

We can't compute everything. We prioritise by benefit to the community, the support a request gathers,
feasibility, and cost, and we explain our reasons when we decline or defer something.

## What we ask of you

- **Open results.** Requests are for datasets we can publish openly. If you send us structures, they must be
  shareable under CC BY 4.0 (or a compatible licence).
- **Use cases.** Tell us how you would use the data; it is the most useful thing in a request.
- **Credit.** If you use a dataset, cite it. Requesters and collaborators are credited in the dataset's record.

See [CONTRIBUTING.md](CONTRIBUTING.md) for what makes a strong request, and
[CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) for how we keep this a good place to work together.

## Licence

The text and templates in this repository are released under [CC BY 4.0](LICENSE). Each dataset states its own
licence in its record (CC BY 4.0 unless stated otherwise).
