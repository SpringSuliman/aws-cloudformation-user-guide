# AWS::AppStream::StackFleetAssociation<a name="aws-resource-appstream-stackfleetassociation"></a>

The `AWS::AppStream::StackFleetAssociation` resource associates the specified fleet with the specified stack for Amazon AppStream 2\.0\. For more information, see [AssociateFleet](https://docs.aws.amazon.com/appstream2/latest/APIReference/API_AssociateFleet.html) in the *Amazon AppStream 2\.0 API Reference*\. 

**Topics**
+ [Syntax](#aws-resource-appstream-stackfleetassociation-syntax)
+ [Properties](#aws-resource-appstream-stackfleetassociation-properties)
+ [See Also](#aws-resource-appstream-stackfleetassociation-seealso)

## Syntax<a name="aws-resource-appstream-stackfleetassociation-syntax"></a>

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON<a name="aws-resource-appstream-stackfleetassociation-syntax.json"></a>

```
{
  "Type" : "AWS::AppStream::StackFleetAssociation",
  "Properties" : {
    "[FleetName](#cfn-appstream-stackfleetassociation-fleetname)" : String,
    "[StackName](#cfn-appstream-stackfleetassociation-stackname)" : String
  }
}
```

### YAML<a name="aws-resource-appstream-stackfleetassociation-syntax.yaml"></a>

```
Type: "AWS::AppStream::StackFleetAssociation"
Properties:
  [FleetName](#cfn-appstream-stackfleetassociation-fleetname): String
  [StackName](#cfn-appstream-stackfleetassociation-stackname): String
```

## Properties<a name="aws-resource-appstream-stackfleetassociation-properties"></a>

`FleetName`  <a name="cfn-appstream-stackfleetassociation-fleetname"></a>
The name of the fleet\.   
To associate a fleet with a stack, you must specify a dependency on the fleet resource\. For more information, see [DependsOn Attribute](aws-attribute-dependson.md)\.  
 *Required*: Yes  
 *Type*: String  
 *Update requires*: [No interruption](using-cfn-updating-stacks-update-behaviors.md#update-no-interrupt) 

`StackName`  <a name="cfn-appstream-stackfleetassociation-stackname"></a>
The name of the stack\.  
To associate a fleet with a stack, you must specify a dependency on the stack resource\. For more information, see [DependsOn Attribute](aws-attribute-dependson.md)\.  
 *Required*: Yes  
 *Type*: String  
 *Update requires*: [No interruption](using-cfn-updating-stacks-update-behaviors.md#update-no-interrupt) 

## See Also<a name="aws-resource-appstream-stackfleetassociation-seealso"></a>
+ [AssociateFleet](https://docs.aws.amazon.com/appstream2/latest/APIReference/API_AssociateFleet.html) in the *Amazon AppStream 2\.0 API Reference*