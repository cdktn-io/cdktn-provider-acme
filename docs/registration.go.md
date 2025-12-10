# `registration` Submodule <a name="`registration` Submodule" id="@cdktf/provider-acme.registration"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### Registration <a name="Registration" id="@cdktf/provider-acme.registration.Registration"></a>

Represents a {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/registration acme_registration}.

#### Initializers <a name="Initializers" id="@cdktf/provider-acme.registration.Registration.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-acme-go/acme/v12/registration"

registration.NewRegistration(scope Construct, id *string, config RegistrationConfig) Registration
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-acme.registration.Registration.Initializer.parameter.scope">scope</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktf/provider-acme.registration.Registration.Initializer.parameter.id">id</a></code> | <code>*string</code> | The scoped construct ID. |
| <code><a href="#@cdktf/provider-acme.registration.Registration.Initializer.parameter.config">config</a></code> | <code><a href="#@cdktf/provider-acme.registration.RegistrationConfig">RegistrationConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktf/provider-acme.registration.Registration.Initializer.parameter.scope"></a>

- *Type:* github.com/aws/constructs-go/constructs/v10.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-acme.registration.Registration.Initializer.parameter.id"></a>

- *Type:* *string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="config" id="@cdktf/provider-acme.registration.Registration.Initializer.parameter.config"></a>

- *Type:* <a href="#@cdktf/provider-acme.registration.RegistrationConfig">RegistrationConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-acme.registration.Registration.toString">ToString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktf/provider-acme.registration.Registration.addOverride">AddOverride</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.overrideLogicalId">OverrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktf/provider-acme.registration.Registration.resetOverrideLogicalId">ResetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktf/provider-acme.registration.Registration.toHclTerraform">ToHclTerraform</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.toMetadata">ToMetadata</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.toTerraform">ToTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktf/provider-acme.registration.Registration.addMoveTarget">AddMoveTarget</a></code> | Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move. |
| <code><a href="#@cdktf/provider-acme.registration.Registration.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.hasResourceMove">HasResourceMove</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.importFrom">ImportFrom</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.moveFromId">MoveFromId</a></code> | Move the resource corresponding to "id" to this resource. |
| <code><a href="#@cdktf/provider-acme.registration.Registration.moveTo">MoveTo</a></code> | Moves this resource to the target resource given by moveTarget. |
| <code><a href="#@cdktf/provider-acme.registration.Registration.moveToId">MoveToId</a></code> | Moves this resource to the resource corresponding to "id". |
| <code><a href="#@cdktf/provider-acme.registration.Registration.putExternalAccountBinding">PutExternalAccountBinding</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.resetAccountKeyAlgorithm">ResetAccountKeyAlgorithm</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.resetAccountKeyEcdsaCurve">ResetAccountKeyEcdsaCurve</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.resetAccountKeyPem">ResetAccountKeyPem</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.resetAccountKeyRsaBits">ResetAccountKeyRsaBits</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.resetExternalAccountBinding">ResetExternalAccountBinding</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.resetId">ResetId</a></code> | *No description.* |

---

##### `ToString` <a name="ToString" id="@cdktf/provider-acme.registration.Registration.toString"></a>

```go
func ToString() *string
```

Returns a string representation of this construct.

##### `AddOverride` <a name="AddOverride" id="@cdktf/provider-acme.registration.Registration.addOverride"></a>

```go
func AddOverride(path *string, value interface{})
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktf/provider-acme.registration.Registration.addOverride.parameter.path"></a>

- *Type:* *string

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-acme.registration.Registration.addOverride.parameter.value"></a>

- *Type:* interface{}

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="@cdktf/provider-acme.registration.Registration.overrideLogicalId"></a>

```go
func OverrideLogicalId(newLogicalId *string)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@cdktf/provider-acme.registration.Registration.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* *string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="@cdktf/provider-acme.registration.Registration.resetOverrideLogicalId"></a>

```go
func ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToHclTerraform` <a name="ToHclTerraform" id="@cdktf/provider-acme.registration.Registration.toHclTerraform"></a>

```go
func ToHclTerraform() interface{}
```

##### `ToMetadata` <a name="ToMetadata" id="@cdktf/provider-acme.registration.Registration.toMetadata"></a>

```go
func ToMetadata() interface{}
```

##### `ToTerraform` <a name="ToTerraform" id="@cdktf/provider-acme.registration.Registration.toTerraform"></a>

```go
func ToTerraform() interface{}
```

Adds this resource to the terraform JSON output.

##### `AddMoveTarget` <a name="AddMoveTarget" id="@cdktf/provider-acme.registration.Registration.addMoveTarget"></a>

```go
func AddMoveTarget(moveTarget *string)
```

Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktf/provider-acme.registration.Registration.addMoveTarget.parameter.moveTarget"></a>

- *Type:* *string

The string move target that will correspond to this resource.

---

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktf/provider-acme.registration.Registration.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.registration.Registration.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktf/provider-acme.registration.Registration.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.registration.Registration.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktf/provider-acme.registration.Registration.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.registration.Registration.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktf/provider-acme.registration.Registration.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.registration.Registration.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktf/provider-acme.registration.Registration.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.registration.Registration.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktf/provider-acme.registration.Registration.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.registration.Registration.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktf/provider-acme.registration.Registration.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.registration.Registration.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktf/provider-acme.registration.Registration.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.registration.Registration.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktf/provider-acme.registration.Registration.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.registration.Registration.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `HasResourceMove` <a name="HasResourceMove" id="@cdktf/provider-acme.registration.Registration.hasResourceMove"></a>

```go
func HasResourceMove() interface{}
```

##### `ImportFrom` <a name="ImportFrom" id="@cdktf/provider-acme.registration.Registration.importFrom"></a>

```go
func ImportFrom(id *string, provider TerraformProvider)
```

###### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-acme.registration.Registration.importFrom.parameter.id"></a>

- *Type:* *string

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-acme.registration.Registration.importFrom.parameter.provider"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktf/provider-acme.registration.Registration.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.registration.Registration.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `MoveFromId` <a name="MoveFromId" id="@cdktf/provider-acme.registration.Registration.moveFromId"></a>

```go
func MoveFromId(id *string)
```

Move the resource corresponding to "id" to this resource.

Note that the resource being moved from must be marked as moved using it's instance function.

###### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-acme.registration.Registration.moveFromId.parameter.id"></a>

- *Type:* *string

Full id of resource being moved from, e.g. "aws_s3_bucket.example".

---

##### `MoveTo` <a name="MoveTo" id="@cdktf/provider-acme.registration.Registration.moveTo"></a>

```go
func MoveTo(moveTarget *string, index interface{})
```

Moves this resource to the target resource given by moveTarget.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktf/provider-acme.registration.Registration.moveTo.parameter.moveTarget"></a>

- *Type:* *string

The previously set user defined string set by .addMoveTarget() corresponding to the resource to move to.

---

###### `index`<sup>Optional</sup> <a name="index" id="@cdktf/provider-acme.registration.Registration.moveTo.parameter.index"></a>

- *Type:* interface{}

Optional The index corresponding to the key the resource is to appear in the foreach of a resource to move to.

---

##### `MoveToId` <a name="MoveToId" id="@cdktf/provider-acme.registration.Registration.moveToId"></a>

```go
func MoveToId(id *string)
```

Moves this resource to the resource corresponding to "id".

###### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-acme.registration.Registration.moveToId.parameter.id"></a>

- *Type:* *string

Full id of resource to move to, e.g. "aws_s3_bucket.example".

---

##### `PutExternalAccountBinding` <a name="PutExternalAccountBinding" id="@cdktf/provider-acme.registration.Registration.putExternalAccountBinding"></a>

```go
func PutExternalAccountBinding(value RegistrationExternalAccountBinding)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-acme.registration.Registration.putExternalAccountBinding.parameter.value"></a>

- *Type:* <a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBinding">RegistrationExternalAccountBinding</a>

---

##### `ResetAccountKeyAlgorithm` <a name="ResetAccountKeyAlgorithm" id="@cdktf/provider-acme.registration.Registration.resetAccountKeyAlgorithm"></a>

```go
func ResetAccountKeyAlgorithm()
```

##### `ResetAccountKeyEcdsaCurve` <a name="ResetAccountKeyEcdsaCurve" id="@cdktf/provider-acme.registration.Registration.resetAccountKeyEcdsaCurve"></a>

```go
func ResetAccountKeyEcdsaCurve()
```

##### `ResetAccountKeyPem` <a name="ResetAccountKeyPem" id="@cdktf/provider-acme.registration.Registration.resetAccountKeyPem"></a>

```go
func ResetAccountKeyPem()
```

##### `ResetAccountKeyRsaBits` <a name="ResetAccountKeyRsaBits" id="@cdktf/provider-acme.registration.Registration.resetAccountKeyRsaBits"></a>

```go
func ResetAccountKeyRsaBits()
```

##### `ResetExternalAccountBinding` <a name="ResetExternalAccountBinding" id="@cdktf/provider-acme.registration.Registration.resetExternalAccountBinding"></a>

```go
func ResetExternalAccountBinding()
```

##### `ResetId` <a name="ResetId" id="@cdktf/provider-acme.registration.Registration.resetId"></a>

```go
func ResetId()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-acme.registration.Registration.isConstruct">IsConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktf/provider-acme.registration.Registration.isTerraformElement">IsTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.isTerraformResource">IsTerraformResource</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.generateConfigForImport">GenerateConfigForImport</a></code> | Generates CDKTF code for importing a Registration resource upon running "cdktf plan <stack-name>". |

---

##### `IsConstruct` <a name="IsConstruct" id="@cdktf/provider-acme.registration.Registration.isConstruct"></a>

```go
import "github.com/cdktf/cdktf-provider-acme-go/acme/v12/registration"

registration.Registration_IsConstruct(x interface{}) *bool
```

Checks if `x` is a construct.

Use this method instead of `instanceof` to properly detect `Construct`
instances, even when the construct library is symlinked.

Explanation: in JavaScript, multiple copies of the `constructs` library on
disk are seen as independent, completely different libraries. As a
consequence, the class `Construct` in each copy of the `constructs` library
is seen as a different class, and an instance of one class will not test as
`instanceof` the other class. `npm install` will not create installations
like this, but users may manually symlink construct libraries together or
use a monorepo tool: in those cases, multiple copies of the `constructs`
library can be accidentally installed, and `instanceof` will behave
unpredictably. It is safest to avoid using `instanceof`, and using
this type-testing method instead.

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-acme.registration.Registration.isConstruct.parameter.x"></a>

- *Type:* interface{}

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="@cdktf/provider-acme.registration.Registration.isTerraformElement"></a>

```go
import "github.com/cdktf/cdktf-provider-acme-go/acme/v12/registration"

registration.Registration_IsTerraformElement(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-acme.registration.Registration.isTerraformElement.parameter.x"></a>

- *Type:* interface{}

---

##### `IsTerraformResource` <a name="IsTerraformResource" id="@cdktf/provider-acme.registration.Registration.isTerraformResource"></a>

```go
import "github.com/cdktf/cdktf-provider-acme-go/acme/v12/registration"

registration.Registration_IsTerraformResource(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-acme.registration.Registration.isTerraformResource.parameter.x"></a>

- *Type:* interface{}

---

##### `GenerateConfigForImport` <a name="GenerateConfigForImport" id="@cdktf/provider-acme.registration.Registration.generateConfigForImport"></a>

```go
import "github.com/cdktf/cdktf-provider-acme-go/acme/v12/registration"

registration.Registration_GenerateConfigForImport(scope Construct, importToId *string, importFromId *string, provider TerraformProvider) ImportableResource
```

Generates CDKTF code for importing a Registration resource upon running "cdktf plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktf/provider-acme.registration.Registration.generateConfigForImport.parameter.scope"></a>

- *Type:* github.com/aws/constructs-go/constructs/v10.Construct

The scope in which to define this construct.

---

###### `importToId`<sup>Required</sup> <a name="importToId" id="@cdktf/provider-acme.registration.Registration.generateConfigForImport.parameter.importToId"></a>

- *Type:* *string

The construct id used in the generated config for the Registration to import.

---

###### `importFromId`<sup>Required</sup> <a name="importFromId" id="@cdktf/provider-acme.registration.Registration.generateConfigForImport.parameter.importFromId"></a>

- *Type:* *string

The id of the existing Registration that should be imported.

Refer to the {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/registration#import import section} in the documentation of this resource for the id to use

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-acme.registration.Registration.generateConfigForImport.parameter.provider"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

? Optional instance of the provider where the Registration to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-acme.registration.Registration.property.node">Node</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Node</code> | The tree node. |
| <code><a href="#@cdktf/provider-acme.registration.Registration.property.cdktfStack">CdktfStack</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>*map[string]interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.property.terraformResourceType">TerraformResourceType</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.property.connection">Connection</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.property.count">Count</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.property.dependsOn">DependsOn</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.property.forEach">ForEach</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.property.lifecycle">Lifecycle</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.property.provider">Provider</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.property.provisioners">Provisioners</a></code> | <code>*[]interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.property.externalAccountBinding">ExternalAccountBinding</a></code> | <code><a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference">RegistrationExternalAccountBindingOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.property.registrationUrl">RegistrationUrl</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.property.accountKeyAlgorithmInput">AccountKeyAlgorithmInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.property.accountKeyEcdsaCurveInput">AccountKeyEcdsaCurveInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.property.accountKeyPemInput">AccountKeyPemInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.property.accountKeyRsaBitsInput">AccountKeyRsaBitsInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.property.emailAddressInput">EmailAddressInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.property.externalAccountBindingInput">ExternalAccountBindingInput</a></code> | <code><a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBinding">RegistrationExternalAccountBinding</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.property.idInput">IdInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.property.accountKeyAlgorithm">AccountKeyAlgorithm</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.property.accountKeyEcdsaCurve">AccountKeyEcdsaCurve</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.property.accountKeyPem">AccountKeyPem</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.property.accountKeyRsaBits">AccountKeyRsaBits</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.property.emailAddress">EmailAddress</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.Registration.property.id">Id</a></code> | <code>*string</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="@cdktf/provider-acme.registration.Registration.property.node"></a>

```go
func Node() Node
```

- *Type:* github.com/aws/constructs-go/constructs/v10.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="@cdktf/provider-acme.registration.Registration.property.cdktfStack"></a>

```go
func CdktfStack() TerraformStack
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-acme.registration.Registration.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="@cdktf/provider-acme.registration.Registration.property.friendlyUniqueId"></a>

```go
func FriendlyUniqueId() *string
```

- *Type:* *string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="@cdktf/provider-acme.registration.Registration.property.terraformMetaArguments"></a>

```go
func TerraformMetaArguments() *map[string]interface{}
```

- *Type:* *map[string]interface{}

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="@cdktf/provider-acme.registration.Registration.property.terraformResourceType"></a>

```go
func TerraformResourceType() *string
```

- *Type:* *string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="@cdktf/provider-acme.registration.Registration.property.terraformGeneratorMetadata"></a>

```go
func TerraformGeneratorMetadata() TerraformProviderGeneratorMetadata
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProviderGeneratorMetadata

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktf/provider-acme.registration.Registration.property.connection"></a>

```go
func Connection() interface{}
```

- *Type:* interface{}

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktf/provider-acme.registration.Registration.property.count"></a>

```go
func Count() interface{}
```

- *Type:* interface{}

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktf/provider-acme.registration.Registration.property.dependsOn"></a>

```go
func DependsOn() *[]*string
```

- *Type:* *[]*string

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktf/provider-acme.registration.Registration.property.forEach"></a>

```go
func ForEach() ITerraformIterator
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktf/provider-acme.registration.Registration.property.lifecycle"></a>

```go
func Lifecycle() TerraformResourceLifecycle
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktf/provider-acme.registration.Registration.property.provider"></a>

```go
func Provider() TerraformProvider
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktf/provider-acme.registration.Registration.property.provisioners"></a>

```go
func Provisioners() *[]interface{}
```

- *Type:* *[]interface{}

---

##### `ExternalAccountBinding`<sup>Required</sup> <a name="ExternalAccountBinding" id="@cdktf/provider-acme.registration.Registration.property.externalAccountBinding"></a>

```go
func ExternalAccountBinding() RegistrationExternalAccountBindingOutputReference
```

- *Type:* <a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference">RegistrationExternalAccountBindingOutputReference</a>

---

##### `RegistrationUrl`<sup>Required</sup> <a name="RegistrationUrl" id="@cdktf/provider-acme.registration.Registration.property.registrationUrl"></a>

```go
func RegistrationUrl() *string
```

- *Type:* *string

---

##### `AccountKeyAlgorithmInput`<sup>Optional</sup> <a name="AccountKeyAlgorithmInput" id="@cdktf/provider-acme.registration.Registration.property.accountKeyAlgorithmInput"></a>

```go
func AccountKeyAlgorithmInput() *string
```

- *Type:* *string

---

##### `AccountKeyEcdsaCurveInput`<sup>Optional</sup> <a name="AccountKeyEcdsaCurveInput" id="@cdktf/provider-acme.registration.Registration.property.accountKeyEcdsaCurveInput"></a>

```go
func AccountKeyEcdsaCurveInput() *string
```

- *Type:* *string

---

##### `AccountKeyPemInput`<sup>Optional</sup> <a name="AccountKeyPemInput" id="@cdktf/provider-acme.registration.Registration.property.accountKeyPemInput"></a>

```go
func AccountKeyPemInput() *string
```

- *Type:* *string

---

##### `AccountKeyRsaBitsInput`<sup>Optional</sup> <a name="AccountKeyRsaBitsInput" id="@cdktf/provider-acme.registration.Registration.property.accountKeyRsaBitsInput"></a>

```go
func AccountKeyRsaBitsInput() *f64
```

- *Type:* *f64

---

##### `EmailAddressInput`<sup>Optional</sup> <a name="EmailAddressInput" id="@cdktf/provider-acme.registration.Registration.property.emailAddressInput"></a>

```go
func EmailAddressInput() *string
```

- *Type:* *string

---

##### `ExternalAccountBindingInput`<sup>Optional</sup> <a name="ExternalAccountBindingInput" id="@cdktf/provider-acme.registration.Registration.property.externalAccountBindingInput"></a>

```go
func ExternalAccountBindingInput() RegistrationExternalAccountBinding
```

- *Type:* <a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBinding">RegistrationExternalAccountBinding</a>

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="@cdktf/provider-acme.registration.Registration.property.idInput"></a>

```go
func IdInput() *string
```

- *Type:* *string

---

##### `AccountKeyAlgorithm`<sup>Required</sup> <a name="AccountKeyAlgorithm" id="@cdktf/provider-acme.registration.Registration.property.accountKeyAlgorithm"></a>

```go
func AccountKeyAlgorithm() *string
```

- *Type:* *string

---

##### `AccountKeyEcdsaCurve`<sup>Required</sup> <a name="AccountKeyEcdsaCurve" id="@cdktf/provider-acme.registration.Registration.property.accountKeyEcdsaCurve"></a>

```go
func AccountKeyEcdsaCurve() *string
```

- *Type:* *string

---

##### `AccountKeyPem`<sup>Required</sup> <a name="AccountKeyPem" id="@cdktf/provider-acme.registration.Registration.property.accountKeyPem"></a>

```go
func AccountKeyPem() *string
```

- *Type:* *string

---

##### `AccountKeyRsaBits`<sup>Required</sup> <a name="AccountKeyRsaBits" id="@cdktf/provider-acme.registration.Registration.property.accountKeyRsaBits"></a>

```go
func AccountKeyRsaBits() *f64
```

- *Type:* *f64

---

##### `EmailAddress`<sup>Required</sup> <a name="EmailAddress" id="@cdktf/provider-acme.registration.Registration.property.emailAddress"></a>

```go
func EmailAddress() *string
```

- *Type:* *string

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktf/provider-acme.registration.Registration.property.id"></a>

```go
func Id() *string
```

- *Type:* *string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-acme.registration.Registration.property.tfResourceType">TfResourceType</a></code> | <code>*string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="@cdktf/provider-acme.registration.Registration.property.tfResourceType"></a>

```go
func TfResourceType() *string
```

- *Type:* *string

---

## Structs <a name="Structs" id="Structs"></a>

### RegistrationConfig <a name="RegistrationConfig" id="@cdktf/provider-acme.registration.RegistrationConfig"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-acme.registration.RegistrationConfig.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-acme-go/acme/v12/registration"

&registration.RegistrationConfig {
	Connection: interface{},
	Count: interface{},
	DependsOn: *[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable,
	ForEach: github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator,
	Lifecycle: github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle,
	Provider: github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider,
	Provisioners: *[]interface{},
	EmailAddress: *string,
	AccountKeyAlgorithm: *string,
	AccountKeyEcdsaCurve: *string,
	AccountKeyPem: *string,
	AccountKeyRsaBits: *f64,
	ExternalAccountBinding: github.com/cdktf/cdktf-provider-acme-go/acme/v12.registration.RegistrationExternalAccountBinding,
	Id: *string,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationConfig.property.connection">Connection</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationConfig.property.count">Count</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationConfig.property.dependsOn">DependsOn</a></code> | <code>*[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationConfig.property.forEach">ForEach</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationConfig.property.lifecycle">Lifecycle</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationConfig.property.provider">Provider</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationConfig.property.provisioners">Provisioners</a></code> | <code>*[]interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationConfig.property.emailAddress">EmailAddress</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/registration#email_address Registration#email_address}. |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationConfig.property.accountKeyAlgorithm">AccountKeyAlgorithm</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/registration#account_key_algorithm Registration#account_key_algorithm}. |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationConfig.property.accountKeyEcdsaCurve">AccountKeyEcdsaCurve</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/registration#account_key_ecdsa_curve Registration#account_key_ecdsa_curve}. |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationConfig.property.accountKeyPem">AccountKeyPem</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/registration#account_key_pem Registration#account_key_pem}. |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationConfig.property.accountKeyRsaBits">AccountKeyRsaBits</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/registration#account_key_rsa_bits Registration#account_key_rsa_bits}. |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationConfig.property.externalAccountBinding">ExternalAccountBinding</a></code> | <code><a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBinding">RegistrationExternalAccountBinding</a></code> | external_account_binding block. |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationConfig.property.id">Id</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/registration#id Registration#id}. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktf/provider-acme.registration.RegistrationConfig.property.connection"></a>

```go
Connection interface{}
```

- *Type:* interface{}

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktf/provider-acme.registration.RegistrationConfig.property.count"></a>

```go
Count interface{}
```

- *Type:* interface{}

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktf/provider-acme.registration.RegistrationConfig.property.dependsOn"></a>

```go
DependsOn *[]ITerraformDependable
```

- *Type:* *[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktf/provider-acme.registration.RegistrationConfig.property.forEach"></a>

```go
ForEach ITerraformIterator
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktf/provider-acme.registration.RegistrationConfig.property.lifecycle"></a>

```go
Lifecycle TerraformResourceLifecycle
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktf/provider-acme.registration.RegistrationConfig.property.provider"></a>

```go
Provider TerraformProvider
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktf/provider-acme.registration.RegistrationConfig.property.provisioners"></a>

```go
Provisioners *[]interface{}
```

- *Type:* *[]interface{}

---

##### `EmailAddress`<sup>Required</sup> <a name="EmailAddress" id="@cdktf/provider-acme.registration.RegistrationConfig.property.emailAddress"></a>

```go
EmailAddress *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/registration#email_address Registration#email_address}.

---

##### `AccountKeyAlgorithm`<sup>Optional</sup> <a name="AccountKeyAlgorithm" id="@cdktf/provider-acme.registration.RegistrationConfig.property.accountKeyAlgorithm"></a>

```go
AccountKeyAlgorithm *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/registration#account_key_algorithm Registration#account_key_algorithm}.

---

##### `AccountKeyEcdsaCurve`<sup>Optional</sup> <a name="AccountKeyEcdsaCurve" id="@cdktf/provider-acme.registration.RegistrationConfig.property.accountKeyEcdsaCurve"></a>

```go
AccountKeyEcdsaCurve *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/registration#account_key_ecdsa_curve Registration#account_key_ecdsa_curve}.

---

##### `AccountKeyPem`<sup>Optional</sup> <a name="AccountKeyPem" id="@cdktf/provider-acme.registration.RegistrationConfig.property.accountKeyPem"></a>

```go
AccountKeyPem *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/registration#account_key_pem Registration#account_key_pem}.

---

##### `AccountKeyRsaBits`<sup>Optional</sup> <a name="AccountKeyRsaBits" id="@cdktf/provider-acme.registration.RegistrationConfig.property.accountKeyRsaBits"></a>

```go
AccountKeyRsaBits *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/registration#account_key_rsa_bits Registration#account_key_rsa_bits}.

---

##### `ExternalAccountBinding`<sup>Optional</sup> <a name="ExternalAccountBinding" id="@cdktf/provider-acme.registration.RegistrationConfig.property.externalAccountBinding"></a>

```go
ExternalAccountBinding RegistrationExternalAccountBinding
```

- *Type:* <a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBinding">RegistrationExternalAccountBinding</a>

external_account_binding block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/registration#external_account_binding Registration#external_account_binding}

---

##### `Id`<sup>Optional</sup> <a name="Id" id="@cdktf/provider-acme.registration.RegistrationConfig.property.id"></a>

```go
Id *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/registration#id Registration#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

### RegistrationExternalAccountBinding <a name="RegistrationExternalAccountBinding" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBinding"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBinding.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-acme-go/acme/v12/registration"

&registration.RegistrationExternalAccountBinding {
	HmacBase64: *string,
	KeyId: *string,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBinding.property.hmacBase64">HmacBase64</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/registration#hmac_base64 Registration#hmac_base64}. |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBinding.property.keyId">KeyId</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/registration#key_id Registration#key_id}. |

---

##### `HmacBase64`<sup>Required</sup> <a name="HmacBase64" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBinding.property.hmacBase64"></a>

```go
HmacBase64 *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/registration#hmac_base64 Registration#hmac_base64}.

---

##### `KeyId`<sup>Required</sup> <a name="KeyId" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBinding.property.keyId"></a>

```go
KeyId *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/registration#key_id Registration#key_id}.

---

## Classes <a name="Classes" id="Classes"></a>

### RegistrationExternalAccountBindingOutputReference <a name="RegistrationExternalAccountBindingOutputReference" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-acme-go/acme/v12/registration"

registration.NewRegistrationExternalAccountBindingOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string) RegistrationExternalAccountBindingOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.hmacBase64Input">HmacBase64Input</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.keyIdInput">KeyIdInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.hmacBase64">HmacBase64</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.keyId">KeyId</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.internalValue">InternalValue</a></code> | <code><a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBinding">RegistrationExternalAccountBinding</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `HmacBase64Input`<sup>Optional</sup> <a name="HmacBase64Input" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.hmacBase64Input"></a>

```go
func HmacBase64Input() *string
```

- *Type:* *string

---

##### `KeyIdInput`<sup>Optional</sup> <a name="KeyIdInput" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.keyIdInput"></a>

```go
func KeyIdInput() *string
```

- *Type:* *string

---

##### `HmacBase64`<sup>Required</sup> <a name="HmacBase64" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.hmacBase64"></a>

```go
func HmacBase64() *string
```

- *Type:* *string

---

##### `KeyId`<sup>Required</sup> <a name="KeyId" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.keyId"></a>

```go
func KeyId() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktf/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.internalValue"></a>

```go
func InternalValue() RegistrationExternalAccountBinding
```

- *Type:* <a href="#@cdktf/provider-acme.registration.RegistrationExternalAccountBinding">RegistrationExternalAccountBinding</a>

---



