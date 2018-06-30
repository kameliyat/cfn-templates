cfn-templates

##################################################################################################################
#### The following file is an example of how to write the Approval Rules for Resource Type AWS::SSM::PatchBaseline
####
#### The RuleGroup property type specifies a set of rules that define the Approval Rules for
#### an Amazon EC2 Systems Manager patch baseline [1].
#### RuleGroup is the property type for the ApprovalRules property of the AWS::SSM::PatchBaseline resource.
#### The "PatchRules" property should be a list of "SSM PatchBaseline Rule" as per [2].
#### The "PatchFilters" property type should be a list of "SSM PatchBaseline PatchFilter" as per [3]
#### and it should be written in a key-value pair format as per [4].
####
#### References:
#### [1] Approval Rules: https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-ssm-patchbaseline.html#aws-resource-ssm-patchbaseline-syntax.json
#### [2] Amazon EC2 Systems Manager PatchBaseline RuleGroup: https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-properties-ssm-patchbaseline-rulegroup.html#aws-properties-ssm-patchbaseline-rulegroup-syntax.json
#### [3] PatchFilters: https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-properties-ssm-patchbaseline-patchfiltergroup.html#aws-properties-ssm-patchbaseline-patchfiltergroup-properties
#### [4] Amazon EC2 Systems Manager PatchBaseline PatchFilter: https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-properties-ssm-patchbaseline-patchfilter.html
#### [5] PatchFilter values: https://docs.aws.amazon.com/systems-manager/latest/APIReference/API_PatchFilter.html
##################################################################################################################
