# Open Security Controls Assessment Language (OSCAL)
[![CircleCI](https://circleci.com/gh/usnistgov/OSCAL/tree/master.svg?style=svg)](https://circleci.com/gh/usnistgov/OSCAL/tree/master) [![Gitter](https://img.shields.io/gitter/room/usnistgov-OSCAL/Lobby.svg?style=flat-square)](https://gitter.im/usnistgov-OSCAL/Lobby)

NIST is [developing](https://csrc.nist.gov/Projects/Open-Security-Controls-Assessment-Language) the Open Security Controls Assessment Language (OSCAL), a set of hierarchical, XML-, JSON-, and YAML-based formats that provide a standardized representations of information pertaining to the publication, implementation, and assessment of security controls. OSCAL is being developed through a [collaborative approach](https://github.com/usnistgov/OSCAL/blob/master/CONTRIBUTING.md) with the public. Public contributions to this project are welcome.

With this effort, we are stressing the agile development of a *minimal* format that is both generic enough to capture the breadth of data in scope (controls specifications), while also capable of ad-hoc tuning and extension to support peculiarities of both (industry or sector) standard and new control types.

The [OSCAL website](https://www.nist.gov/oscal) provides an overview of the OSCAL project, including an XML and JSON [schema reference](https://pages.nist.gov/OSCAL/docs/schemas/), [examples](https://pages.nist.gov/OSCAL/resources/examples/), and other resources.

If you are interested in supporting the development of the standard, refer to the [contributor guidance](https://github.com/usnistgov/OSCAL/blob/master/CONTRIBUTING.md) for more information.

## Project Status

OSCAL 1.0.0 Release Candidate 1 was released on December 21, 2020. The full announcement can be found below:

<blockquote>
We are pleased to announce the publication of OSCAL 1.0.0 Release Candidate (RC) 1. This is a full draft release of OSCAL 1.0.0 which is made available for public review and feedback before releasing the final OSCAL 1.0.0.

The [OSCAL 1.0.0 RC 1](https://github.com/usnistgov/OSCAL/releases/tag/v1.0.0-rc1) includes:

- Updated stable versions of [catalog](https://pages.nist.gov/OSCAL/documentation/schema/catalog-layer/catalog/) and [profile](https://pages.nist.gov/OSCAL/documentation/schema/profile-layer/profile/) models which provide a structured representation of control catalogs and baselines or overlays.
- Updated stable version of the [system security plan](https://pages.nist.gov/OSCAL/documentation/schema/implementation-layer/ssp/) model which provides a structured representations of a system&#39;s control-based implementation. This model has been enhanced to support documenting how controls from an existing authorized system can be leveraged in another information system, which supports common control provider and platform as a service (PaaS) use cases.
- Updated stable version of the [component definition](https://pages.nist.gov/OSCAL/documentation/schema/implementation-layer/component/) model which provides a structured representation of the controls that are supported in a given implementation of a hardware, software, service, policy, process, procedure, or compliance artifact (e.g., FIPS 140-2 validation).
- Revised drafts of the [assessment plan](https://pages.nist.gov/OSCAL/documentation/schema/assessment-layer/assessment-plan/), [assessment results](https://pages.nist.gov/OSCAL/documentation/schema/assessment-results-layer/assessment-results/), [plan of action and milestones](https://pages.nist.gov/OSCAL/documentation/schema/assessment-results-layer/poam/) (POA&amp;M) models, which support the structured representation of information used for planning and documenting the results of an information system assessment or continuous monitoring activity. These models have been enhanced to better support continuous assessment; to provide more traceability between the assessment schedule, specific assessment activities, collected data, and resulting findings and identified risks; and to improve the extensibility of these models.
- Updated tools to convert between OSCAL [XML](https://github.com/usnistgov/OSCAL/tree/master/xml) and [JSON](https://github.com/usnistgov/OSCAL/tree/master/json) formats, and to [up convert](https://github.com/usnistgov/OSCAL/tree/master/src/release/content-upgrade) content from milestone 3 to RC1.

These changes were made based on all the excellent feedback we received from the OSCAL community. The NIST OSCAL team is very thankful for all of the great feedback we have received.

The NIST team is also maintaining **OSCAL content** that is updated to the latest OSCAL 1.0.0 RC1. The OSCAL [content repository](https://github.com/usnistgov/oscal-content/) provides OSCAL examples, in addition to the final [NIST SP 800-53 revision 5 catalog](https://github.com/usnistgov/oscal-content/tree/master/nist.gov/SP800-53/rev5) and the final security and privacy [NIST SP 800-53B baselines](https://github.com/usnistgov/oscal-content/tree/master/nist.gov/SP800-53/rev5). All this content is provided in XML, JSON and YAML formats, including the following:

- Updated content for the [NIST SP 800-53 revision 4 catalogs](https://github.com/usnistgov/oscal-content/tree/master/nist.gov/SP800-53/rev4), and for the [three NIST baselines](https://github.com/usnistgov/oscal-content/tree/master/nist.gov/SP800-53/rev4).
- Updated content in OSCAL XML, JSON and YAML formats of the [FedRAMP SP 800-53 revision 4 baselines](https://github.com/usnistgov/oscal-content/tree/master/fedramp.gov). Please note, these baselines are also available on [GSA/fedramp-automation](https://github.com/GSA/fedramp-automation/tree/master/baselines) repository.

There are also [release notes](https://github.com/usnistgov/OSCAL/blob/master/src/release/release-notes.txt) containing a summary of changes in this and previous releases.

The OSCAL team is working to release OSCAL 1.0.0 FINAL. To this end, we appreciate any feedback you have on the updated RC1 models. Receiving your comments is instrumental for our team to make the OSCAL 1.0.0 FINAL release as robust as is feasible, and to address any gaps that might cause backwards compatibilities between future OSCAL minor releases (e.g., 1.1.0, 1.2.0) and OSCAL 1.0.0.

At our end, we will continue the development of OSCAL focusing our full attention on providing a more complete set of documentation for all the OSCAL layers and models, creating more examples, and providing a diverse set of tutorials.

NIST is also seeking tool developers, vendors, and service providers that would like to implement the OSCAL 1.0.0 models in commercial and open-source offerings. To provide feedback, to ask questions, or to let us know about an OSCAL implementation you are working on, please email the NIST OSCAL team at [oscal@nist.gov](mailto:oscal@nist.gov). You can also post publicly to the OSCAL development list: [oscal-dev@list.nist.gov](mailto:oscal-dev@list.nist.gov) or [create an issue](https://github.com/usnistgov/OSCAL/issues) on our GitHub repository.

Please find instructions for joining the OSCAL development and update lists on our [contacts page](https://pages.nist.gov/OSCAL/contact/).
</blockquote>

NIST is seeking software and service providers that are willing to work with us to represent control implementation information about their products. Please email us at [oscal@nist.gov](mailto:oscal@nist.gov) if you are interested.

If you have any questions about OSCAL in general or if you would like to get involved in the OSCAL project, please contact us at: [oscal@nist.gov](mailto:oscal@nist.gov) or on [Gitter](https://gitter.im/usnistgov-OSCAL/Lobby).