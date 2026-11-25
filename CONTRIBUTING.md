# Contributing a dataset idea

Thank you for helping us decide what to compute. This page explains what makes a request easy to act on and
how the conversation works.

## Before you start

- **Search first.** Someone may already have asked for something close; supporting and refining an existing
  request often beats opening a new one.
- **Rough is fine.** You don't need a finished design. A clear use case with "I'm not sure" in half the fields
  is a good request; we work out the details with you.

## What makes a strong request

1. **The use case.** What will the data let you, or others, do that you can't do today? Training or
   benchmarking machine-learned potentials, testing a method, screening, teaching, a gap in an existing
   benchmark set...
2. **The chemical space.** Which molecules or materials, which elements, charges and spin states, and what
   size range. A source of structures if you have one (an existing dataset, a list of SMILES, a generation
   rule).
3. **The properties.** Energies, forces, Hessians and frequencies, dipoles and polarizabilities, charges,
   orbitals, conformer ensembles, reaction paths, solvent effects...
4. **The accuracy you need.** A level of theory if you have one in mind, or what decision the data has to
   support, and we'll suggest the method.
5. **Scale and format.** Roughly how many structures, and the file formats that would make the data easy for
   you to use.
6. **Constraints.** Licences of the structures you provide, deadlines, and anything we should know.

## How the conversation works

- Requests live in [Discussions](https://github.com/atomsforhumanity/datasets/discussions) so everyone can see
  and build on them.
- We label each request with its status: `status: proposed`, `status: needs info`, `status: under review`,
  `status: planned`, `status: computing`, `status: released` or `status: declined`.
- When we decline or defer a request, we say why: cost, overlap with an existing dataset, a licence problem,
  or a better route we can suggest.
- Prefer to talk privately first? Email **datasets@afh.org**.

## Problems with a released dataset

If you find a wrong value, a missing record or a documentation problem, open an
[issue](https://github.com/atomsforhumanity/datasets/issues/new/choose) with the dataset's name and version and
the records concerned. Corrections are released as a new version of the dataset, and the record says what
changed.

## Credit

Requesters and collaborators are named in the dataset's record unless they prefer not to be. Substantial
scientific collaborations, for example jointly designing a dataset and analysing it, can lead to joint
publications; talk to us.
