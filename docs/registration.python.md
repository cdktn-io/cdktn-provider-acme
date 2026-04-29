# `registration` Submodule <a name="`registration` Submodule" id="@cdktn/provider-acme.registration"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### Registration <a name="Registration" id="@cdktn/provider-acme.registration.Registration"></a>

Represents a {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration acme_registration}.

#### Initializers <a name="Initializers" id="@cdktn/provider-acme.registration.Registration.Initializer"></a>

```python
from cdktn_provider_acme import registration

registration.Registration(
  scope: Construct,
  id: str,
  connection: SSHProvisionerConnection | WinrmProvisionerConnection = None,
  count: typing.Union[int, float] | TerraformCount = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner] = None,
  account_key_algorithm: str = None,
  account_key_ecdsa_curve: str = None,
  account_key_pem: str = None,
  account_key_rsa_bits: typing.Union[int, float] = None,
  email_address: str = None,
  external_account_binding: RegistrationExternalAccountBinding = None,
  id: str = None
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.id">id</a></code> | <code>str</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.connection">connection</a></code> | <code>cdktn.SSHProvisionerConnection \| cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.count">count</a></code> | <code>typing.Union[int, float] \| cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.dependsOn">depends_on</a></code> | <code>typing.List[cdktn.ITerraformDependable]</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.forEach">for_each</a></code> | <code>cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.provider">provider</a></code> | <code>cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.provisioners">provisioners</a></code> | <code>typing.List[cdktn.FileProvisioner \| cdktn.LocalExecProvisioner \| cdktn.RemoteExecProvisioner]</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.accountKeyAlgorithm">account_key_algorithm</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#account_key_algorithm Registration#account_key_algorithm}. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.accountKeyEcdsaCurve">account_key_ecdsa_curve</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#account_key_ecdsa_curve Registration#account_key_ecdsa_curve}. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.accountKeyPem">account_key_pem</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#account_key_pem Registration#account_key_pem}. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.accountKeyRsaBits">account_key_rsa_bits</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#account_key_rsa_bits Registration#account_key_rsa_bits}. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.emailAddress">email_address</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#email_address Registration#email_address}. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.externalAccountBinding">external_account_binding</a></code> | <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBinding">RegistrationExternalAccountBinding</a></code> | external_account_binding block. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.id">id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#id Registration#id}. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.id"></a>

- *Type:* str

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.connection"></a>

- *Type:* cdktn.SSHProvisionerConnection | cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.count"></a>

- *Type:* typing.Union[int, float] | cdktn.TerraformCount

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.dependsOn"></a>

- *Type:* typing.List[cdktn.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.forEach"></a>

- *Type:* cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.lifecycle"></a>

- *Type:* cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.provider"></a>

- *Type:* cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.provisioners"></a>

- *Type:* typing.List[cdktn.FileProvisioner | cdktn.LocalExecProvisioner | cdktn.RemoteExecProvisioner]

---

##### `account_key_algorithm`<sup>Optional</sup> <a name="account_key_algorithm" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.accountKeyAlgorithm"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#account_key_algorithm Registration#account_key_algorithm}.

---

##### `account_key_ecdsa_curve`<sup>Optional</sup> <a name="account_key_ecdsa_curve" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.accountKeyEcdsaCurve"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#account_key_ecdsa_curve Registration#account_key_ecdsa_curve}.

---

##### `account_key_pem`<sup>Optional</sup> <a name="account_key_pem" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.accountKeyPem"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#account_key_pem Registration#account_key_pem}.

---

##### `account_key_rsa_bits`<sup>Optional</sup> <a name="account_key_rsa_bits" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.accountKeyRsaBits"></a>

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#account_key_rsa_bits Registration#account_key_rsa_bits}.

---

##### `email_address`<sup>Optional</sup> <a name="email_address" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.emailAddress"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#email_address Registration#email_address}.

---

##### `external_account_binding`<sup>Optional</sup> <a name="external_account_binding" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.externalAccountBinding"></a>

- *Type:* <a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBinding">RegistrationExternalAccountBinding</a>

external_account_binding block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#external_account_binding Registration#external_account_binding}

---

##### `id`<sup>Optional</sup> <a name="id" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.id"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#id Registration#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-acme.registration.Registration.toString">to_string</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.with">with</a></code> | Applies one or more mixins to this construct. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.addOverride">add_override</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.overrideLogicalId">override_logical_id</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.resetOverrideLogicalId">reset_override_logical_id</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.toHclTerraform">to_hcl_terraform</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.toMetadata">to_metadata</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.toTerraform">to_terraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.addMoveTarget">add_move_target</a></code> | Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.hasResourceMove">has_resource_move</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.importFrom">import_from</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.moveFromId">move_from_id</a></code> | Move the resource corresponding to "id" to this resource. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.moveTo">move_to</a></code> | Moves this resource to the target resource given by moveTarget. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.moveToId">move_to_id</a></code> | Moves this resource to the resource corresponding to "id". |
| <code><a href="#@cdktn/provider-acme.registration.Registration.putExternalAccountBinding">put_external_account_binding</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.resetAccountKeyAlgorithm">reset_account_key_algorithm</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.resetAccountKeyEcdsaCurve">reset_account_key_ecdsa_curve</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.resetAccountKeyPem">reset_account_key_pem</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.resetAccountKeyRsaBits">reset_account_key_rsa_bits</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.resetEmailAddress">reset_email_address</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.resetExternalAccountBinding">reset_external_account_binding</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.resetId">reset_id</a></code> | *No description.* |

---

##### `to_string` <a name="to_string" id="@cdktn/provider-acme.registration.Registration.toString"></a>

```python
def to_string() -> str
```

Returns a string representation of this construct.

##### `with` <a name="with" id="@cdktn/provider-acme.registration.Registration.with"></a>

```python
def with(
  mixins: *IMixin
) -> IConstruct
```

Applies one or more mixins to this construct.

Mixins are applied in order. The list of constructs is captured at the
start of the call, so constructs added by a mixin will not be visited.
Use multiple `with()` calls if subsequent mixins should apply to added
constructs.

###### `mixins`<sup>Required</sup> <a name="mixins" id="@cdktn/provider-acme.registration.Registration.with.parameter.mixins"></a>

- *Type:* *constructs.IMixin

The mixins to apply.

---

##### `add_override` <a name="add_override" id="@cdktn/provider-acme.registration.Registration.addOverride"></a>

```python
def add_override(
  path: str,
  value: typing.Any
) -> None
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktn/provider-acme.registration.Registration.addOverride.parameter.path"></a>

- *Type:* str

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-acme.registration.Registration.addOverride.parameter.value"></a>

- *Type:* typing.Any

---

##### `override_logical_id` <a name="override_logical_id" id="@cdktn/provider-acme.registration.Registration.overrideLogicalId"></a>

```python
def override_logical_id(
  new_logical_id: str
) -> None
```

Overrides the auto-generated logical ID with a specific ID.

###### `new_logical_id`<sup>Required</sup> <a name="new_logical_id" id="@cdktn/provider-acme.registration.Registration.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* str

The new logical ID to use for this stack element.

---

##### `reset_override_logical_id` <a name="reset_override_logical_id" id="@cdktn/provider-acme.registration.Registration.resetOverrideLogicalId"></a>

```python
def reset_override_logical_id() -> None
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `to_hcl_terraform` <a name="to_hcl_terraform" id="@cdktn/provider-acme.registration.Registration.toHclTerraform"></a>

```python
def to_hcl_terraform() -> typing.Any
```

##### `to_metadata` <a name="to_metadata" id="@cdktn/provider-acme.registration.Registration.toMetadata"></a>

```python
def to_metadata() -> typing.Any
```

##### `to_terraform` <a name="to_terraform" id="@cdktn/provider-acme.registration.Registration.toTerraform"></a>

```python
def to_terraform() -> typing.Any
```

Adds this resource to the terraform JSON output.

##### `add_move_target` <a name="add_move_target" id="@cdktn/provider-acme.registration.Registration.addMoveTarget"></a>

```python
def add_move_target(
  move_target: str
) -> None
```

Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move.

###### `move_target`<sup>Required</sup> <a name="move_target" id="@cdktn/provider-acme.registration.Registration.addMoveTarget.parameter.moveTarget"></a>

- *Type:* str

The string move target that will correspond to this resource.

---

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="@cdktn/provider-acme.registration.Registration.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-acme.registration.Registration.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="@cdktn/provider-acme.registration.Registration.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-acme.registration.Registration.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="@cdktn/provider-acme.registration.Registration.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-acme.registration.Registration.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="@cdktn/provider-acme.registration.Registration.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-acme.registration.Registration.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="@cdktn/provider-acme.registration.Registration.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-acme.registration.Registration.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="@cdktn/provider-acme.registration.Registration.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-acme.registration.Registration.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="@cdktn/provider-acme.registration.Registration.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-acme.registration.Registration.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="@cdktn/provider-acme.registration.Registration.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-acme.registration.Registration.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="@cdktn/provider-acme.registration.Registration.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-acme.registration.Registration.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `has_resource_move` <a name="has_resource_move" id="@cdktn/provider-acme.registration.Registration.hasResourceMove"></a>

```python
def has_resource_move() -> TerraformResourceMoveByTarget | TerraformResourceMoveById
```

##### `import_from` <a name="import_from" id="@cdktn/provider-acme.registration.Registration.importFrom"></a>

```python
def import_from(
  id: str,
  provider: TerraformProvider = None
) -> None
```

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-acme.registration.Registration.importFrom.parameter.id"></a>

- *Type:* str

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-acme.registration.Registration.importFrom.parameter.provider"></a>

- *Type:* cdktn.TerraformProvider

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="@cdktn/provider-acme.registration.Registration.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-acme.registration.Registration.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `move_from_id` <a name="move_from_id" id="@cdktn/provider-acme.registration.Registration.moveFromId"></a>

```python
def move_from_id(
  id: str
) -> None
```

Move the resource corresponding to "id" to this resource.

Note that the resource being moved from must be marked as moved using it's instance function.

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-acme.registration.Registration.moveFromId.parameter.id"></a>

- *Type:* str

Full id of resource being moved from, e.g. "aws_s3_bucket.example".

---

##### `move_to` <a name="move_to" id="@cdktn/provider-acme.registration.Registration.moveTo"></a>

```python
def move_to(
  move_target: str,
  index: str | typing.Union[int, float] = None
) -> None
```

Moves this resource to the target resource given by moveTarget.

###### `move_target`<sup>Required</sup> <a name="move_target" id="@cdktn/provider-acme.registration.Registration.moveTo.parameter.moveTarget"></a>

- *Type:* str

The previously set user defined string set by .addMoveTarget() corresponding to the resource to move to.

---

###### `index`<sup>Optional</sup> <a name="index" id="@cdktn/provider-acme.registration.Registration.moveTo.parameter.index"></a>

- *Type:* str | typing.Union[int, float]

Optional The index corresponding to the key the resource is to appear in the foreach of a resource to move to.

---

##### `move_to_id` <a name="move_to_id" id="@cdktn/provider-acme.registration.Registration.moveToId"></a>

```python
def move_to_id(
  id: str
) -> None
```

Moves this resource to the resource corresponding to "id".

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-acme.registration.Registration.moveToId.parameter.id"></a>

- *Type:* str

Full id of resource to move to, e.g. "aws_s3_bucket.example".

---

##### `put_external_account_binding` <a name="put_external_account_binding" id="@cdktn/provider-acme.registration.Registration.putExternalAccountBinding"></a>

```python
def put_external_account_binding(
  hmac_base64: str,
  key_id: str
) -> None
```

###### `hmac_base64`<sup>Required</sup> <a name="hmac_base64" id="@cdktn/provider-acme.registration.Registration.putExternalAccountBinding.parameter.hmacBase64"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#hmac_base64 Registration#hmac_base64}.

---

###### `key_id`<sup>Required</sup> <a name="key_id" id="@cdktn/provider-acme.registration.Registration.putExternalAccountBinding.parameter.keyId"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#key_id Registration#key_id}.

---

##### `reset_account_key_algorithm` <a name="reset_account_key_algorithm" id="@cdktn/provider-acme.registration.Registration.resetAccountKeyAlgorithm"></a>

```python
def reset_account_key_algorithm() -> None
```

##### `reset_account_key_ecdsa_curve` <a name="reset_account_key_ecdsa_curve" id="@cdktn/provider-acme.registration.Registration.resetAccountKeyEcdsaCurve"></a>

```python
def reset_account_key_ecdsa_curve() -> None
```

##### `reset_account_key_pem` <a name="reset_account_key_pem" id="@cdktn/provider-acme.registration.Registration.resetAccountKeyPem"></a>

```python
def reset_account_key_pem() -> None
```

##### `reset_account_key_rsa_bits` <a name="reset_account_key_rsa_bits" id="@cdktn/provider-acme.registration.Registration.resetAccountKeyRsaBits"></a>

```python
def reset_account_key_rsa_bits() -> None
```

##### `reset_email_address` <a name="reset_email_address" id="@cdktn/provider-acme.registration.Registration.resetEmailAddress"></a>

```python
def reset_email_address() -> None
```

##### `reset_external_account_binding` <a name="reset_external_account_binding" id="@cdktn/provider-acme.registration.Registration.resetExternalAccountBinding"></a>

```python
def reset_external_account_binding() -> None
```

##### `reset_id` <a name="reset_id" id="@cdktn/provider-acme.registration.Registration.resetId"></a>

```python
def reset_id() -> None
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-acme.registration.Registration.isConstruct">is_construct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.isTerraformElement">is_terraform_element</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.isTerraformResource">is_terraform_resource</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.generateConfigForImport">generate_config_for_import</a></code> | Generates CDKTN code for importing a Registration resource upon running "cdktn plan <stack-name>". |

---

##### `is_construct` <a name="is_construct" id="@cdktn/provider-acme.registration.Registration.isConstruct"></a>

```python
from cdktn_provider_acme import registration

registration.Registration.is_construct(
  x: typing.Any
)
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

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-acme.registration.Registration.isConstruct.parameter.x"></a>

- *Type:* typing.Any

Any object.

---

##### `is_terraform_element` <a name="is_terraform_element" id="@cdktn/provider-acme.registration.Registration.isTerraformElement"></a>

```python
from cdktn_provider_acme import registration

registration.Registration.is_terraform_element(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-acme.registration.Registration.isTerraformElement.parameter.x"></a>

- *Type:* typing.Any

---

##### `is_terraform_resource` <a name="is_terraform_resource" id="@cdktn/provider-acme.registration.Registration.isTerraformResource"></a>

```python
from cdktn_provider_acme import registration

registration.Registration.is_terraform_resource(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-acme.registration.Registration.isTerraformResource.parameter.x"></a>

- *Type:* typing.Any

---

##### `generate_config_for_import` <a name="generate_config_for_import" id="@cdktn/provider-acme.registration.Registration.generateConfigForImport"></a>

```python
from cdktn_provider_acme import registration

registration.Registration.generate_config_for_import(
  scope: Construct,
  import_to_id: str,
  import_from_id: str,
  provider: TerraformProvider = None
)
```

Generates CDKTN code for importing a Registration resource upon running "cdktn plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-acme.registration.Registration.generateConfigForImport.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

###### `import_to_id`<sup>Required</sup> <a name="import_to_id" id="@cdktn/provider-acme.registration.Registration.generateConfigForImport.parameter.importToId"></a>

- *Type:* str

The construct id used in the generated config for the Registration to import.

---

###### `import_from_id`<sup>Required</sup> <a name="import_from_id" id="@cdktn/provider-acme.registration.Registration.generateConfigForImport.parameter.importFromId"></a>

- *Type:* str

The id of the existing Registration that should be imported.

Refer to the {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#import import section} in the documentation of this resource for the id to use

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-acme.registration.Registration.generateConfigForImport.parameter.provider"></a>

- *Type:* cdktn.TerraformProvider

? Optional instance of the provider where the Registration to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.cdktfStack">cdktf_stack</a></code> | <code>cdktn.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.friendlyUniqueId">friendly_unique_id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.terraformMetaArguments">terraform_meta_arguments</a></code> | <code>typing.Mapping[typing.Any]</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.terraformResourceType">terraform_resource_type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.terraformGeneratorMetadata">terraform_generator_metadata</a></code> | <code>cdktn.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.connection">connection</a></code> | <code>cdktn.SSHProvisionerConnection \| cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.count">count</a></code> | <code>typing.Union[int, float] \| cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.dependsOn">depends_on</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.forEach">for_each</a></code> | <code>cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.lifecycle">lifecycle</a></code> | <code>cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.provider">provider</a></code> | <code>cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.provisioners">provisioners</a></code> | <code>typing.List[cdktn.FileProvisioner \| cdktn.LocalExecProvisioner \| cdktn.RemoteExecProvisioner]</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.externalAccountBinding">external_account_binding</a></code> | <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference">RegistrationExternalAccountBindingOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.registrationUrl">registration_url</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.accountKeyAlgorithmInput">account_key_algorithm_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.accountKeyEcdsaCurveInput">account_key_ecdsa_curve_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.accountKeyPemInput">account_key_pem_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.accountKeyRsaBitsInput">account_key_rsa_bits_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.emailAddressInput">email_address_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.externalAccountBindingInput">external_account_binding_input</a></code> | <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBinding">RegistrationExternalAccountBinding</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.idInput">id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.accountKeyAlgorithm">account_key_algorithm</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.accountKeyEcdsaCurve">account_key_ecdsa_curve</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.accountKeyPem">account_key_pem</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.accountKeyRsaBits">account_key_rsa_bits</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.emailAddress">email_address</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.id">id</a></code> | <code>str</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="@cdktn/provider-acme.registration.Registration.property.node"></a>

```python
node: Node
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktf_stack`<sup>Required</sup> <a name="cdktf_stack" id="@cdktn/provider-acme.registration.Registration.property.cdktfStack"></a>

```python
cdktf_stack: TerraformStack
```

- *Type:* cdktn.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-acme.registration.Registration.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `friendly_unique_id`<sup>Required</sup> <a name="friendly_unique_id" id="@cdktn/provider-acme.registration.Registration.property.friendlyUniqueId"></a>

```python
friendly_unique_id: str
```

- *Type:* str

---

##### `terraform_meta_arguments`<sup>Required</sup> <a name="terraform_meta_arguments" id="@cdktn/provider-acme.registration.Registration.property.terraformMetaArguments"></a>

```python
terraform_meta_arguments: typing.Mapping[typing.Any]
```

- *Type:* typing.Mapping[typing.Any]

---

##### `terraform_resource_type`<sup>Required</sup> <a name="terraform_resource_type" id="@cdktn/provider-acme.registration.Registration.property.terraformResourceType"></a>

```python
terraform_resource_type: str
```

- *Type:* str

---

##### `terraform_generator_metadata`<sup>Optional</sup> <a name="terraform_generator_metadata" id="@cdktn/provider-acme.registration.Registration.property.terraformGeneratorMetadata"></a>

```python
terraform_generator_metadata: TerraformProviderGeneratorMetadata
```

- *Type:* cdktn.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-acme.registration.Registration.property.connection"></a>

```python
connection: SSHProvisionerConnection | WinrmProvisionerConnection
```

- *Type:* cdktn.SSHProvisionerConnection | cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-acme.registration.Registration.property.count"></a>

```python
count: typing.Union[int, float] | TerraformCount
```

- *Type:* typing.Union[int, float] | cdktn.TerraformCount

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="@cdktn/provider-acme.registration.Registration.property.dependsOn"></a>

```python
depends_on: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="@cdktn/provider-acme.registration.Registration.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-acme.registration.Registration.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-acme.registration.Registration.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-acme.registration.Registration.property.provisioners"></a>

```python
provisioners: typing.List[FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner]
```

- *Type:* typing.List[cdktn.FileProvisioner | cdktn.LocalExecProvisioner | cdktn.RemoteExecProvisioner]

---

##### `external_account_binding`<sup>Required</sup> <a name="external_account_binding" id="@cdktn/provider-acme.registration.Registration.property.externalAccountBinding"></a>

```python
external_account_binding: RegistrationExternalAccountBindingOutputReference
```

- *Type:* <a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference">RegistrationExternalAccountBindingOutputReference</a>

---

##### `registration_url`<sup>Required</sup> <a name="registration_url" id="@cdktn/provider-acme.registration.Registration.property.registrationUrl"></a>

```python
registration_url: str
```

- *Type:* str

---

##### `account_key_algorithm_input`<sup>Optional</sup> <a name="account_key_algorithm_input" id="@cdktn/provider-acme.registration.Registration.property.accountKeyAlgorithmInput"></a>

```python
account_key_algorithm_input: str
```

- *Type:* str

---

##### `account_key_ecdsa_curve_input`<sup>Optional</sup> <a name="account_key_ecdsa_curve_input" id="@cdktn/provider-acme.registration.Registration.property.accountKeyEcdsaCurveInput"></a>

```python
account_key_ecdsa_curve_input: str
```

- *Type:* str

---

##### `account_key_pem_input`<sup>Optional</sup> <a name="account_key_pem_input" id="@cdktn/provider-acme.registration.Registration.property.accountKeyPemInput"></a>

```python
account_key_pem_input: str
```

- *Type:* str

---

##### `account_key_rsa_bits_input`<sup>Optional</sup> <a name="account_key_rsa_bits_input" id="@cdktn/provider-acme.registration.Registration.property.accountKeyRsaBitsInput"></a>

```python
account_key_rsa_bits_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `email_address_input`<sup>Optional</sup> <a name="email_address_input" id="@cdktn/provider-acme.registration.Registration.property.emailAddressInput"></a>

```python
email_address_input: str
```

- *Type:* str

---

##### `external_account_binding_input`<sup>Optional</sup> <a name="external_account_binding_input" id="@cdktn/provider-acme.registration.Registration.property.externalAccountBindingInput"></a>

```python
external_account_binding_input: RegistrationExternalAccountBinding
```

- *Type:* <a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBinding">RegistrationExternalAccountBinding</a>

---

##### `id_input`<sup>Optional</sup> <a name="id_input" id="@cdktn/provider-acme.registration.Registration.property.idInput"></a>

```python
id_input: str
```

- *Type:* str

---

##### `account_key_algorithm`<sup>Required</sup> <a name="account_key_algorithm" id="@cdktn/provider-acme.registration.Registration.property.accountKeyAlgorithm"></a>

```python
account_key_algorithm: str
```

- *Type:* str

---

##### `account_key_ecdsa_curve`<sup>Required</sup> <a name="account_key_ecdsa_curve" id="@cdktn/provider-acme.registration.Registration.property.accountKeyEcdsaCurve"></a>

```python
account_key_ecdsa_curve: str
```

- *Type:* str

---

##### `account_key_pem`<sup>Required</sup> <a name="account_key_pem" id="@cdktn/provider-acme.registration.Registration.property.accountKeyPem"></a>

```python
account_key_pem: str
```

- *Type:* str

---

##### `account_key_rsa_bits`<sup>Required</sup> <a name="account_key_rsa_bits" id="@cdktn/provider-acme.registration.Registration.property.accountKeyRsaBits"></a>

```python
account_key_rsa_bits: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `email_address`<sup>Required</sup> <a name="email_address" id="@cdktn/provider-acme.registration.Registration.property.emailAddress"></a>

```python
email_address: str
```

- *Type:* str

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-acme.registration.Registration.property.id"></a>

```python
id: str
```

- *Type:* str

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.tfResourceType">tfResourceType</a></code> | <code>str</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="@cdktn/provider-acme.registration.Registration.property.tfResourceType"></a>

```python
tfResourceType: str
```

- *Type:* str

---

## Structs <a name="Structs" id="Structs"></a>

### RegistrationConfig <a name="RegistrationConfig" id="@cdktn/provider-acme.registration.RegistrationConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-acme.registration.RegistrationConfig.Initializer"></a>

```python
from cdktn_provider_acme import registration

registration.RegistrationConfig(
  connection: SSHProvisionerConnection | WinrmProvisionerConnection = None,
  count: typing.Union[int, float] | TerraformCount = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner] = None,
  account_key_algorithm: str = None,
  account_key_ecdsa_curve: str = None,
  account_key_pem: str = None,
  account_key_rsa_bits: typing.Union[int, float] = None,
  email_address: str = None,
  external_account_binding: RegistrationExternalAccountBinding = None,
  id: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationConfig.property.connection">connection</a></code> | <code>cdktn.SSHProvisionerConnection \| cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationConfig.property.count">count</a></code> | <code>typing.Union[int, float] \| cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationConfig.property.dependsOn">depends_on</a></code> | <code>typing.List[cdktn.ITerraformDependable]</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationConfig.property.forEach">for_each</a></code> | <code>cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationConfig.property.lifecycle">lifecycle</a></code> | <code>cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationConfig.property.provider">provider</a></code> | <code>cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationConfig.property.provisioners">provisioners</a></code> | <code>typing.List[cdktn.FileProvisioner \| cdktn.LocalExecProvisioner \| cdktn.RemoteExecProvisioner]</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationConfig.property.accountKeyAlgorithm">account_key_algorithm</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#account_key_algorithm Registration#account_key_algorithm}. |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationConfig.property.accountKeyEcdsaCurve">account_key_ecdsa_curve</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#account_key_ecdsa_curve Registration#account_key_ecdsa_curve}. |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationConfig.property.accountKeyPem">account_key_pem</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#account_key_pem Registration#account_key_pem}. |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationConfig.property.accountKeyRsaBits">account_key_rsa_bits</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#account_key_rsa_bits Registration#account_key_rsa_bits}. |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationConfig.property.emailAddress">email_address</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#email_address Registration#email_address}. |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationConfig.property.externalAccountBinding">external_account_binding</a></code> | <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBinding">RegistrationExternalAccountBinding</a></code> | external_account_binding block. |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationConfig.property.id">id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#id Registration#id}. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-acme.registration.RegistrationConfig.property.connection"></a>

```python
connection: SSHProvisionerConnection | WinrmProvisionerConnection
```

- *Type:* cdktn.SSHProvisionerConnection | cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-acme.registration.RegistrationConfig.property.count"></a>

```python
count: typing.Union[int, float] | TerraformCount
```

- *Type:* typing.Union[int, float] | cdktn.TerraformCount

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="@cdktn/provider-acme.registration.RegistrationConfig.property.dependsOn"></a>

```python
depends_on: typing.List[ITerraformDependable]
```

- *Type:* typing.List[cdktn.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="@cdktn/provider-acme.registration.RegistrationConfig.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-acme.registration.RegistrationConfig.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-acme.registration.RegistrationConfig.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-acme.registration.RegistrationConfig.property.provisioners"></a>

```python
provisioners: typing.List[FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner]
```

- *Type:* typing.List[cdktn.FileProvisioner | cdktn.LocalExecProvisioner | cdktn.RemoteExecProvisioner]

---

##### `account_key_algorithm`<sup>Optional</sup> <a name="account_key_algorithm" id="@cdktn/provider-acme.registration.RegistrationConfig.property.accountKeyAlgorithm"></a>

```python
account_key_algorithm: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#account_key_algorithm Registration#account_key_algorithm}.

---

##### `account_key_ecdsa_curve`<sup>Optional</sup> <a name="account_key_ecdsa_curve" id="@cdktn/provider-acme.registration.RegistrationConfig.property.accountKeyEcdsaCurve"></a>

```python
account_key_ecdsa_curve: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#account_key_ecdsa_curve Registration#account_key_ecdsa_curve}.

---

##### `account_key_pem`<sup>Optional</sup> <a name="account_key_pem" id="@cdktn/provider-acme.registration.RegistrationConfig.property.accountKeyPem"></a>

```python
account_key_pem: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#account_key_pem Registration#account_key_pem}.

---

##### `account_key_rsa_bits`<sup>Optional</sup> <a name="account_key_rsa_bits" id="@cdktn/provider-acme.registration.RegistrationConfig.property.accountKeyRsaBits"></a>

```python
account_key_rsa_bits: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#account_key_rsa_bits Registration#account_key_rsa_bits}.

---

##### `email_address`<sup>Optional</sup> <a name="email_address" id="@cdktn/provider-acme.registration.RegistrationConfig.property.emailAddress"></a>

```python
email_address: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#email_address Registration#email_address}.

---

##### `external_account_binding`<sup>Optional</sup> <a name="external_account_binding" id="@cdktn/provider-acme.registration.RegistrationConfig.property.externalAccountBinding"></a>

```python
external_account_binding: RegistrationExternalAccountBinding
```

- *Type:* <a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBinding">RegistrationExternalAccountBinding</a>

external_account_binding block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#external_account_binding Registration#external_account_binding}

---

##### `id`<sup>Optional</sup> <a name="id" id="@cdktn/provider-acme.registration.RegistrationConfig.property.id"></a>

```python
id: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#id Registration#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

### RegistrationExternalAccountBinding <a name="RegistrationExternalAccountBinding" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBinding"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBinding.Initializer"></a>

```python
from cdktn_provider_acme import registration

registration.RegistrationExternalAccountBinding(
  hmac_base64: str,
  key_id: str
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBinding.property.hmacBase64">hmac_base64</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#hmac_base64 Registration#hmac_base64}. |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBinding.property.keyId">key_id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#key_id Registration#key_id}. |

---

##### `hmac_base64`<sup>Required</sup> <a name="hmac_base64" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBinding.property.hmacBase64"></a>

```python
hmac_base64: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#hmac_base64 Registration#hmac_base64}.

---

##### `key_id`<sup>Required</sup> <a name="key_id" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBinding.property.keyId"></a>

```python
key_id: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.1/docs/resources/registration#key_id Registration#key_id}.

---

## Classes <a name="Classes" id="Classes"></a>

### RegistrationExternalAccountBindingOutputReference <a name="RegistrationExternalAccountBindingOutputReference" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.Initializer"></a>

```python
from cdktn_provider_acme import registration

registration.RegistrationExternalAccountBindingOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktn.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |

---

##### `compute_fqn` <a name="compute_fqn" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.resolve.parameter._context"></a>

- *Type:* cdktn.IResolveContext

---

##### `to_string` <a name="to_string" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.hmacBase64Input">hmac_base64_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.keyIdInput">key_id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.hmacBase64">hmac_base64</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.keyId">key_id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.internalValue">internal_value</a></code> | <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBinding">RegistrationExternalAccountBinding</a></code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `hmac_base64_input`<sup>Optional</sup> <a name="hmac_base64_input" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.hmacBase64Input"></a>

```python
hmac_base64_input: str
```

- *Type:* str

---

##### `key_id_input`<sup>Optional</sup> <a name="key_id_input" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.keyIdInput"></a>

```python
key_id_input: str
```

- *Type:* str

---

##### `hmac_base64`<sup>Required</sup> <a name="hmac_base64" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.hmacBase64"></a>

```python
hmac_base64: str
```

- *Type:* str

---

##### `key_id`<sup>Required</sup> <a name="key_id" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.keyId"></a>

```python
key_id: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.internalValue"></a>

```python
internal_value: RegistrationExternalAccountBinding
```

- *Type:* <a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBinding">RegistrationExternalAccountBinding</a>

---



