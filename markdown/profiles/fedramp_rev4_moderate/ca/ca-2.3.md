---
x-trestle-global:
  profile-title: FedRAMP Rev 4 Moderate Baseline
x-trestle-set-params:
  ca-2.3_prm_1:
    profile-values:
    values:
  ca-2.3_prm_2:
    profile-values:
    values:
  ca-2.3_prm_3:
    profile-values:
    values:
sort-id: ca-02.03
x-trestle-add-props:
  # Add or modify control properties here
  # Properties may be at the control or part level
  # Add control level properties like this:
  #   - name: ac1_new_prop
  #     value: new property value
  #
  # Add properties to a statement part like this, where "b." is the label of the target statement part
  #   - name: ac1_new_prop
  #     value: new property value
  #     smt-part: b.
  #
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ca-2.3_obj.1
  - name: method
    value: EXAMINE
    smt-part: ca-2.3_obj.1
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ca-2.3_obj.2
  - name: method
    value: EXAMINE
    smt-part: ca-2.3_obj.2
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ca-2.3_obj.3
  - name: method
    value: EXAMINE
    smt-part: ca-2.3_obj.3
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ca-2.3_obj.4
  - name: method
    value: EXAMINE
    smt-part: ca-2.3_obj.4
  - name: method
    value: INTERVIEW
    smt-part: ca-2.3_obj.4
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ca-2.3_smt
---

# ca-2.3 - \[Security Assessment and Authorization\] External Organizations

## Control Statement

The organization accepts the results of an assessment of {{ insert: param, ca-2.3_prm_1 }} performed by {{ insert: param, ca-2.3_prm_2 }} when the assessment meets {{ insert: param, ca-2.3_prm_3 }}.

## Control Objective

Determine if the organization:

- \[CA-2(3)[1]\] defines an information system for which the results of a security assessment performed by an external organization are to be accepted;

- \[CA-2(3)[2]\] defines an external organization from which to accept a security assessment performed on an organization-defined information system;

- \[CA-2(3)[3]\] defines the requirements to be met by a security assessment performed by organization-defined external organization on organization-defined information system; and

- \[CA-2(3)[4]\] accepts the results of an assessment of an organization-defined information system performed by an organization-defined external organization when the assessment meets organization-defined requirements.

## Control guidance

Organizations may often rely on assessments of specific information systems by other (external) organizations. Utilizing such existing assessments (i.e., reusing existing assessment evidence) can significantly decrease the time and resources required for organizational assessments by limiting the amount of independent assessment activities that organizations need to perform. The factors that organizations may consider in determining whether to accept assessment results from external organizations can vary. Determinations for accepting assessment results can be based on, for example, past assessment experiences one organization has had with another organization, the reputation that organizations have with regard to assessments, the level of detail of supporting assessment documentation provided, or mandates imposed upon organizations by federal legislation, policies, or directives.

# Editable Content

<!-- Make additions and edits below -->
<!-- The above represents the contents of the control as received by the profile, prior to additions. -->
<!-- If the profile makes additions to the control, they will appear below. -->
<!-- The above markdown may not be edited but you may edit the content below, and/or introduce new additions to be made by the profile. -->
<!-- If there is a yaml header at the top, parameter values may be edited. Use --set-parameters to incorporate the changes during assembly. -->
<!-- The content here will then replace what is in the profile for this control, after running profile-assemble. -->
<!-- The added parts in the profile for this control are below.  You may edit them and/or add new ones. -->
<!-- Each addition must have a heading either of the form ## Control my_addition_name -->
<!-- or ## Part a. (where the a. refers to one of the control statement labels.) -->
<!-- "## Control" parts are new parts added after the statement part. -->
<!-- "## Part" parts are new parts added into the top-level statement part with that label. -->
<!-- Subparts may be added with nested hash levels of the form ### My Subpart Name -->
<!-- underneath the parent ## Control or ## Part being added -->
<!-- See https://ibm.github.io/compliance-trestle/tutorials/ssp_profile_catalog_authoring/ssp_profile_catalog_authoring for guidance. -->