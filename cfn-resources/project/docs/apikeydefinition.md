# MongoDB::Atlas::Project apiKeyDefinition

## Syntax

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON

<pre>
{
    "<a href="#publickey" title="PublicKey">PublicKey</a>" : <i>String</i>,
    "<a href="#privatekey" title="PrivateKey">PrivateKey</a>" : <i>String</i>
}
</pre>

### YAML

<pre>
<a href="#publickey" title="PublicKey">PublicKey</a>: <i>String</i>
<a href="#privatekey" title="PrivateKey">PrivateKey</a>: <i>String</i>
</pre>

## Properties

#### PublicKey

_Required_: No

_Type_: String

_Pattern_: <code>{{resolve:.*:[a-zA-Z0-9_.-/]+}}</code>

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

#### PrivateKey

_Required_: No

_Type_: String

_Pattern_: <code>{{resolve:.*:[a-zA-Z0-9_.-/]+}}</code>

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)
