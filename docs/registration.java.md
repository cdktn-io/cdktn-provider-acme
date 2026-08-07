# `registration` Submodule <a name="`registration` Submodule" id="@cdktn/provider-acme.registration"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### Registration <a name="Registration" id="@cdktn/provider-acme.registration.Registration"></a>

Represents a {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration acme_registration}.

#### Initializers <a name="Initializers" id="@cdktn/provider-acme.registration.Registration.Initializer"></a>

```java
import io.cdktn.providers.acme.registration.Registration;

Registration.Builder.create(Construct scope, java.lang.String id)
//  .connection(SSHProvisionerConnection|WinrmProvisionerConnection)
//  .count(java.lang.Number|TerraformCount)
//  .dependsOn(java.util.List<ITerraformDependable>)
//  .forEach(ITerraformIterator)
//  .lifecycle(TerraformResourceLifecycle)
//  .provider(TerraformProvider)
//  .provisioners(java.util.List<FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner>)
//  .accountKeyAlgorithm(java.lang.String)
//  .accountKeyEcdsaCurve(java.lang.String)
//  .accountKeyPem(java.lang.String)
//  .accountKeyRsaBits(java.lang.Number)
//  .emailAddress(java.lang.String)
//  .externalAccountBinding(RegistrationExternalAccountBinding)
//  .id(java.lang.String)
    .build();
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.scope">scope</a></code> | <code>software.constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.id">id</a></code> | <code>java.lang.String</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.connection">connection</a></code> | <code>io.cdktn.cdktn.SSHProvisionerConnection\|io.cdktn.cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.count">count</a></code> | <code>java.lang.Number\|io.cdktn.cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.dependsOn">dependsOn</a></code> | <code>java.util.List<io.cdktn.cdktn.ITerraformDependable></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.forEach">forEach</a></code> | <code>io.cdktn.cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>io.cdktn.cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.provider">provider</a></code> | <code>io.cdktn.cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.provisioners">provisioners</a></code> | <code>java.util.List<io.cdktn.cdktn.FileProvisioner\|io.cdktn.cdktn.LocalExecProvisioner\|io.cdktn.cdktn.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.accountKeyAlgorithm">accountKeyAlgorithm</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration#account_key_algorithm Registration#account_key_algorithm}. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.accountKeyEcdsaCurve">accountKeyEcdsaCurve</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration#account_key_ecdsa_curve Registration#account_key_ecdsa_curve}. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.accountKeyPem">accountKeyPem</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration#account_key_pem Registration#account_key_pem}. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.accountKeyRsaBits">accountKeyRsaBits</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration#account_key_rsa_bits Registration#account_key_rsa_bits}. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.emailAddress">emailAddress</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration#email_address Registration#email_address}. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.externalAccountBinding">externalAccountBinding</a></code> | <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBinding">RegistrationExternalAccountBinding</a></code> | external_account_binding block. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.Initializer.parameter.id">id</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration#id Registration#id}. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.scope"></a>

- *Type:* software.constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.id"></a>

- *Type:* java.lang.String

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.connection"></a>

- *Type:* io.cdktn.cdktn.SSHProvisionerConnection|io.cdktn.cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.count"></a>

- *Type:* java.lang.Number|io.cdktn.cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.dependsOn"></a>

- *Type:* java.util.List<io.cdktn.cdktn.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.forEach"></a>

- *Type:* io.cdktn.cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.lifecycle"></a>

- *Type:* io.cdktn.cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.provider"></a>

- *Type:* io.cdktn.cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.provisioners"></a>

- *Type:* java.util.List<io.cdktn.cdktn.FileProvisioner|io.cdktn.cdktn.LocalExecProvisioner|io.cdktn.cdktn.RemoteExecProvisioner>

---

##### `accountKeyAlgorithm`<sup>Optional</sup> <a name="accountKeyAlgorithm" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.accountKeyAlgorithm"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration#account_key_algorithm Registration#account_key_algorithm}.

---

##### `accountKeyEcdsaCurve`<sup>Optional</sup> <a name="accountKeyEcdsaCurve" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.accountKeyEcdsaCurve"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration#account_key_ecdsa_curve Registration#account_key_ecdsa_curve}.

---

##### `accountKeyPem`<sup>Optional</sup> <a name="accountKeyPem" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.accountKeyPem"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration#account_key_pem Registration#account_key_pem}.

---

##### `accountKeyRsaBits`<sup>Optional</sup> <a name="accountKeyRsaBits" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.accountKeyRsaBits"></a>

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration#account_key_rsa_bits Registration#account_key_rsa_bits}.

---

##### `emailAddress`<sup>Optional</sup> <a name="emailAddress" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.emailAddress"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration#email_address Registration#email_address}.

---

##### `externalAccountBinding`<sup>Optional</sup> <a name="externalAccountBinding" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.externalAccountBinding"></a>

- *Type:* <a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBinding">RegistrationExternalAccountBinding</a>

external_account_binding block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration#external_account_binding Registration#external_account_binding}

---

##### `id`<sup>Optional</sup> <a name="id" id="@cdktn/provider-acme.registration.Registration.Initializer.parameter.id"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration#id Registration#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-acme.registration.Registration.toString">toString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.with">with</a></code> | Applies one or more mixins to this construct. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.addOverride">addOverride</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.overrideLogicalId">overrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.resetOverrideLogicalId">resetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.toHclTerraform">toHclTerraform</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.toMetadata">toMetadata</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.toTerraform">toTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.addMoveTarget">addMoveTarget</a></code> | Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.hasResourceMove">hasResourceMove</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.importFrom">importFrom</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.moveFromId">moveFromId</a></code> | Move the resource corresponding to "id" to this resource. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.moveTo">moveTo</a></code> | Moves this resource to the target resource given by moveTarget. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.moveToId">moveToId</a></code> | Moves this resource to the resource corresponding to "id". |
| <code><a href="#@cdktn/provider-acme.registration.Registration.putExternalAccountBinding">putExternalAccountBinding</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.resetAccountKeyAlgorithm">resetAccountKeyAlgorithm</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.resetAccountKeyEcdsaCurve">resetAccountKeyEcdsaCurve</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.resetAccountKeyPem">resetAccountKeyPem</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.resetAccountKeyRsaBits">resetAccountKeyRsaBits</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.resetEmailAddress">resetEmailAddress</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.resetExternalAccountBinding">resetExternalAccountBinding</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.resetId">resetId</a></code> | *No description.* |

---

##### `toString` <a name="toString" id="@cdktn/provider-acme.registration.Registration.toString"></a>

```java
public java.lang.String toString()
```

Returns a string representation of this construct.

##### `with` <a name="with" id="@cdktn/provider-acme.registration.Registration.with"></a>

```java
public IConstruct with(IMixin... mixins)
```

Applies one or more mixins to this construct.

Mixins are applied in order. The list of constructs is captured at the
start of the call, so constructs added by a mixin will not be visited.
Use multiple `with()` calls if subsequent mixins should apply to added
constructs.

###### `mixins`<sup>Required</sup> <a name="mixins" id="@cdktn/provider-acme.registration.Registration.with.parameter.mixins"></a>

- *Type:* software.constructs.IMixin...

The mixins to apply.

---

##### `addOverride` <a name="addOverride" id="@cdktn/provider-acme.registration.Registration.addOverride"></a>

```java
public void addOverride(java.lang.String path, java.lang.Object value)
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktn/provider-acme.registration.Registration.addOverride.parameter.path"></a>

- *Type:* java.lang.String

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-acme.registration.Registration.addOverride.parameter.value"></a>

- *Type:* java.lang.Object

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="@cdktn/provider-acme.registration.Registration.overrideLogicalId"></a>

```java
public void overrideLogicalId(java.lang.String newLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@cdktn/provider-acme.registration.Registration.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* java.lang.String

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="@cdktn/provider-acme.registration.Registration.resetOverrideLogicalId"></a>

```java
public void resetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toHclTerraform` <a name="toHclTerraform" id="@cdktn/provider-acme.registration.Registration.toHclTerraform"></a>

```java
public java.lang.Object toHclTerraform()
```

##### `toMetadata` <a name="toMetadata" id="@cdktn/provider-acme.registration.Registration.toMetadata"></a>

```java
public java.lang.Object toMetadata()
```

##### `toTerraform` <a name="toTerraform" id="@cdktn/provider-acme.registration.Registration.toTerraform"></a>

```java
public java.lang.Object toTerraform()
```

Adds this resource to the terraform JSON output.

##### `addMoveTarget` <a name="addMoveTarget" id="@cdktn/provider-acme.registration.Registration.addMoveTarget"></a>

```java
public void addMoveTarget(java.lang.String moveTarget)
```

Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktn/provider-acme.registration.Registration.addMoveTarget.parameter.moveTarget"></a>

- *Type:* java.lang.String

The string move target that will correspond to this resource.

---

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-acme.registration.Registration.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-acme.registration.Registration.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-acme.registration.Registration.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-acme.registration.Registration.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-acme.registration.Registration.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-acme.registration.Registration.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-acme.registration.Registration.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-acme.registration.Registration.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-acme.registration.Registration.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-acme.registration.Registration.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-acme.registration.Registration.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-acme.registration.Registration.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-acme.registration.Registration.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-acme.registration.Registration.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-acme.registration.Registration.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-acme.registration.Registration.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-acme.registration.Registration.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-acme.registration.Registration.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `hasResourceMove` <a name="hasResourceMove" id="@cdktn/provider-acme.registration.Registration.hasResourceMove"></a>

```java
public TerraformResourceMoveByTarget|TerraformResourceMoveById hasResourceMove()
```

##### `importFrom` <a name="importFrom" id="@cdktn/provider-acme.registration.Registration.importFrom"></a>

```java
public void importFrom(java.lang.String id)
public void importFrom(java.lang.String id, TerraformProvider provider)
```

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-acme.registration.Registration.importFrom.parameter.id"></a>

- *Type:* java.lang.String

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-acme.registration.Registration.importFrom.parameter.provider"></a>

- *Type:* io.cdktn.cdktn.TerraformProvider

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-acme.registration.Registration.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-acme.registration.Registration.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `moveFromId` <a name="moveFromId" id="@cdktn/provider-acme.registration.Registration.moveFromId"></a>

```java
public void moveFromId(java.lang.String id)
```

Move the resource corresponding to "id" to this resource.

Note that the resource being moved from must be marked as moved using its instance function.

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-acme.registration.Registration.moveFromId.parameter.id"></a>

- *Type:* java.lang.String

Full id of resource being moved from, e.g. "aws_s3_bucket.example".

---

##### `moveTo` <a name="moveTo" id="@cdktn/provider-acme.registration.Registration.moveTo"></a>

```java
public void moveTo(java.lang.String moveTarget)
public void moveTo(java.lang.String moveTarget, java.lang.String|java.lang.Number index)
```

Moves this resource to the target resource given by moveTarget.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktn/provider-acme.registration.Registration.moveTo.parameter.moveTarget"></a>

- *Type:* java.lang.String

The previously set user defined string set by .addMoveTarget() corresponding to the resource to move to.

---

###### `index`<sup>Optional</sup> <a name="index" id="@cdktn/provider-acme.registration.Registration.moveTo.parameter.index"></a>

- *Type:* java.lang.String|java.lang.Number

Optional The index corresponding to the key the resource is to appear in the foreach of a resource to move to.

---

##### `moveToId` <a name="moveToId" id="@cdktn/provider-acme.registration.Registration.moveToId"></a>

```java
public void moveToId(java.lang.String id)
```

Moves this resource to the resource corresponding to "id".

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-acme.registration.Registration.moveToId.parameter.id"></a>

- *Type:* java.lang.String

Full id of resource to move to, e.g. "aws_s3_bucket.example".

---

##### `putExternalAccountBinding` <a name="putExternalAccountBinding" id="@cdktn/provider-acme.registration.Registration.putExternalAccountBinding"></a>

```java
public void putExternalAccountBinding(RegistrationExternalAccountBinding value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-acme.registration.Registration.putExternalAccountBinding.parameter.value"></a>

- *Type:* <a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBinding">RegistrationExternalAccountBinding</a>

---

##### `resetAccountKeyAlgorithm` <a name="resetAccountKeyAlgorithm" id="@cdktn/provider-acme.registration.Registration.resetAccountKeyAlgorithm"></a>

```java
public void resetAccountKeyAlgorithm()
```

##### `resetAccountKeyEcdsaCurve` <a name="resetAccountKeyEcdsaCurve" id="@cdktn/provider-acme.registration.Registration.resetAccountKeyEcdsaCurve"></a>

```java
public void resetAccountKeyEcdsaCurve()
```

##### `resetAccountKeyPem` <a name="resetAccountKeyPem" id="@cdktn/provider-acme.registration.Registration.resetAccountKeyPem"></a>

```java
public void resetAccountKeyPem()
```

##### `resetAccountKeyRsaBits` <a name="resetAccountKeyRsaBits" id="@cdktn/provider-acme.registration.Registration.resetAccountKeyRsaBits"></a>

```java
public void resetAccountKeyRsaBits()
```

##### `resetEmailAddress` <a name="resetEmailAddress" id="@cdktn/provider-acme.registration.Registration.resetEmailAddress"></a>

```java
public void resetEmailAddress()
```

##### `resetExternalAccountBinding` <a name="resetExternalAccountBinding" id="@cdktn/provider-acme.registration.Registration.resetExternalAccountBinding"></a>

```java
public void resetExternalAccountBinding()
```

##### `resetId` <a name="resetId" id="@cdktn/provider-acme.registration.Registration.resetId"></a>

```java
public void resetId()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-acme.registration.Registration.isConstruct">isConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.isTerraformElement">isTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.isTerraformResource">isTerraformResource</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.generateConfigForImport">generateConfigForImport</a></code> | Generates CDKTN code for importing a Registration resource upon running "cdktn plan <stack-name>". |

---

##### `isConstruct` <a name="isConstruct" id="@cdktn/provider-acme.registration.Registration.isConstruct"></a>

```java
import io.cdktn.providers.acme.registration.Registration;

Registration.isConstruct(java.lang.Object x)
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

- *Type:* java.lang.Object

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="@cdktn/provider-acme.registration.Registration.isTerraformElement"></a>

```java
import io.cdktn.providers.acme.registration.Registration;

Registration.isTerraformElement(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-acme.registration.Registration.isTerraformElement.parameter.x"></a>

- *Type:* java.lang.Object

---

##### `isTerraformResource` <a name="isTerraformResource" id="@cdktn/provider-acme.registration.Registration.isTerraformResource"></a>

```java
import io.cdktn.providers.acme.registration.Registration;

Registration.isTerraformResource(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-acme.registration.Registration.isTerraformResource.parameter.x"></a>

- *Type:* java.lang.Object

---

##### `generateConfigForImport` <a name="generateConfigForImport" id="@cdktn/provider-acme.registration.Registration.generateConfigForImport"></a>

```java
import io.cdktn.providers.acme.registration.Registration;

Registration.generateConfigForImport(Construct scope, java.lang.String importToId, java.lang.String importFromId),Registration.generateConfigForImport(Construct scope, java.lang.String importToId, java.lang.String importFromId, TerraformProvider provider)
```

Generates CDKTN code for importing a Registration resource upon running "cdktn plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-acme.registration.Registration.generateConfigForImport.parameter.scope"></a>

- *Type:* software.constructs.Construct

The scope in which to define this construct.

---

###### `importToId`<sup>Required</sup> <a name="importToId" id="@cdktn/provider-acme.registration.Registration.generateConfigForImport.parameter.importToId"></a>

- *Type:* java.lang.String

The construct id used in the generated config for the Registration to import.

---

###### `importFromId`<sup>Required</sup> <a name="importFromId" id="@cdktn/provider-acme.registration.Registration.generateConfigForImport.parameter.importFromId"></a>

- *Type:* java.lang.String

The id of the existing Registration that should be imported.

Refer to the {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration#import import section} in the documentation of this resource for the id to use

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-acme.registration.Registration.generateConfigForImport.parameter.provider"></a>

- *Type:* io.cdktn.cdktn.TerraformProvider

? Optional instance of the provider where the Registration to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.node">node</a></code> | <code>software.constructs.Node</code> | The tree node. |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.cdktfStack">cdktfStack</a></code> | <code>io.cdktn.cdktn.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>java.util.Map<java.lang.String, java.lang.Object></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.terraformResourceType">terraformResourceType</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>io.cdktn.cdktn.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.connection">connection</a></code> | <code>io.cdktn.cdktn.SSHProvisionerConnection\|io.cdktn.cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.count">count</a></code> | <code>java.lang.Number\|io.cdktn.cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.dependsOn">dependsOn</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.forEach">forEach</a></code> | <code>io.cdktn.cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.lifecycle">lifecycle</a></code> | <code>io.cdktn.cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.provider">provider</a></code> | <code>io.cdktn.cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.provisioners">provisioners</a></code> | <code>java.util.List<io.cdktn.cdktn.FileProvisioner\|io.cdktn.cdktn.LocalExecProvisioner\|io.cdktn.cdktn.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.externalAccountBinding">externalAccountBinding</a></code> | <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference">RegistrationExternalAccountBindingOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.registrationUrl">registrationUrl</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.accountKeyAlgorithmInput">accountKeyAlgorithmInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.accountKeyEcdsaCurveInput">accountKeyEcdsaCurveInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.accountKeyPemInput">accountKeyPemInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.accountKeyRsaBitsInput">accountKeyRsaBitsInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.emailAddressInput">emailAddressInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.externalAccountBindingInput">externalAccountBindingInput</a></code> | <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBinding">RegistrationExternalAccountBinding</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.idInput">idInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.accountKeyAlgorithm">accountKeyAlgorithm</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.accountKeyEcdsaCurve">accountKeyEcdsaCurve</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.accountKeyPem">accountKeyPem</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.accountKeyRsaBits">accountKeyRsaBits</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.emailAddress">emailAddress</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.id">id</a></code> | <code>java.lang.String</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="@cdktn/provider-acme.registration.Registration.property.node"></a>

```java
public Node getNode();
```

- *Type:* software.constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="@cdktn/provider-acme.registration.Registration.property.cdktfStack"></a>

```java
public TerraformStack getCdktfStack();
```

- *Type:* io.cdktn.cdktn.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-acme.registration.Registration.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="@cdktn/provider-acme.registration.Registration.property.friendlyUniqueId"></a>

```java
public java.lang.String getFriendlyUniqueId();
```

- *Type:* java.lang.String

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="@cdktn/provider-acme.registration.Registration.property.terraformMetaArguments"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getTerraformMetaArguments();
```

- *Type:* java.util.Map<java.lang.String, java.lang.Object>

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="@cdktn/provider-acme.registration.Registration.property.terraformResourceType"></a>

```java
public java.lang.String getTerraformResourceType();
```

- *Type:* java.lang.String

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="@cdktn/provider-acme.registration.Registration.property.terraformGeneratorMetadata"></a>

```java
public TerraformProviderGeneratorMetadata getTerraformGeneratorMetadata();
```

- *Type:* io.cdktn.cdktn.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-acme.registration.Registration.property.connection"></a>

```java
public SSHProvisionerConnection|WinrmProvisionerConnection getConnection();
```

- *Type:* io.cdktn.cdktn.SSHProvisionerConnection|io.cdktn.cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-acme.registration.Registration.property.count"></a>

```java
public java.lang.Number|TerraformCount getCount();
```

- *Type:* java.lang.Number|io.cdktn.cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-acme.registration.Registration.property.dependsOn"></a>

```java
public java.util.List<java.lang.String> getDependsOn();
```

- *Type:* java.util.List<java.lang.String>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-acme.registration.Registration.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* io.cdktn.cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-acme.registration.Registration.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* io.cdktn.cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-acme.registration.Registration.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* io.cdktn.cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-acme.registration.Registration.property.provisioners"></a>

```java
public java.util.List<FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner> getProvisioners();
```

- *Type:* java.util.List<io.cdktn.cdktn.FileProvisioner|io.cdktn.cdktn.LocalExecProvisioner|io.cdktn.cdktn.RemoteExecProvisioner>

---

##### `externalAccountBinding`<sup>Required</sup> <a name="externalAccountBinding" id="@cdktn/provider-acme.registration.Registration.property.externalAccountBinding"></a>

```java
public RegistrationExternalAccountBindingOutputReference getExternalAccountBinding();
```

- *Type:* <a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference">RegistrationExternalAccountBindingOutputReference</a>

---

##### `registrationUrl`<sup>Required</sup> <a name="registrationUrl" id="@cdktn/provider-acme.registration.Registration.property.registrationUrl"></a>

```java
public java.lang.String getRegistrationUrl();
```

- *Type:* java.lang.String

---

##### `accountKeyAlgorithmInput`<sup>Optional</sup> <a name="accountKeyAlgorithmInput" id="@cdktn/provider-acme.registration.Registration.property.accountKeyAlgorithmInput"></a>

```java
public java.lang.String getAccountKeyAlgorithmInput();
```

- *Type:* java.lang.String

---

##### `accountKeyEcdsaCurveInput`<sup>Optional</sup> <a name="accountKeyEcdsaCurveInput" id="@cdktn/provider-acme.registration.Registration.property.accountKeyEcdsaCurveInput"></a>

```java
public java.lang.String getAccountKeyEcdsaCurveInput();
```

- *Type:* java.lang.String

---

##### `accountKeyPemInput`<sup>Optional</sup> <a name="accountKeyPemInput" id="@cdktn/provider-acme.registration.Registration.property.accountKeyPemInput"></a>

```java
public java.lang.String getAccountKeyPemInput();
```

- *Type:* java.lang.String

---

##### `accountKeyRsaBitsInput`<sup>Optional</sup> <a name="accountKeyRsaBitsInput" id="@cdktn/provider-acme.registration.Registration.property.accountKeyRsaBitsInput"></a>

```java
public java.lang.Number getAccountKeyRsaBitsInput();
```

- *Type:* java.lang.Number

---

##### `emailAddressInput`<sup>Optional</sup> <a name="emailAddressInput" id="@cdktn/provider-acme.registration.Registration.property.emailAddressInput"></a>

```java
public java.lang.String getEmailAddressInput();
```

- *Type:* java.lang.String

---

##### `externalAccountBindingInput`<sup>Optional</sup> <a name="externalAccountBindingInput" id="@cdktn/provider-acme.registration.Registration.property.externalAccountBindingInput"></a>

```java
public RegistrationExternalAccountBinding getExternalAccountBindingInput();
```

- *Type:* <a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBinding">RegistrationExternalAccountBinding</a>

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="@cdktn/provider-acme.registration.Registration.property.idInput"></a>

```java
public java.lang.String getIdInput();
```

- *Type:* java.lang.String

---

##### `accountKeyAlgorithm`<sup>Required</sup> <a name="accountKeyAlgorithm" id="@cdktn/provider-acme.registration.Registration.property.accountKeyAlgorithm"></a>

```java
public java.lang.String getAccountKeyAlgorithm();
```

- *Type:* java.lang.String

---

##### `accountKeyEcdsaCurve`<sup>Required</sup> <a name="accountKeyEcdsaCurve" id="@cdktn/provider-acme.registration.Registration.property.accountKeyEcdsaCurve"></a>

```java
public java.lang.String getAccountKeyEcdsaCurve();
```

- *Type:* java.lang.String

---

##### `accountKeyPem`<sup>Required</sup> <a name="accountKeyPem" id="@cdktn/provider-acme.registration.Registration.property.accountKeyPem"></a>

```java
public java.lang.String getAccountKeyPem();
```

- *Type:* java.lang.String

---

##### `accountKeyRsaBits`<sup>Required</sup> <a name="accountKeyRsaBits" id="@cdktn/provider-acme.registration.Registration.property.accountKeyRsaBits"></a>

```java
public java.lang.Number getAccountKeyRsaBits();
```

- *Type:* java.lang.Number

---

##### `emailAddress`<sup>Required</sup> <a name="emailAddress" id="@cdktn/provider-acme.registration.Registration.property.emailAddress"></a>

```java
public java.lang.String getEmailAddress();
```

- *Type:* java.lang.String

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-acme.registration.Registration.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-acme.registration.Registration.property.tfResourceType">tfResourceType</a></code> | <code>java.lang.String</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="@cdktn/provider-acme.registration.Registration.property.tfResourceType"></a>

```java
public java.lang.String getTfResourceType();
```

- *Type:* java.lang.String

---

## Structs <a name="Structs" id="Structs"></a>

### RegistrationConfig <a name="RegistrationConfig" id="@cdktn/provider-acme.registration.RegistrationConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-acme.registration.RegistrationConfig.Initializer"></a>

```java
import io.cdktn.providers.acme.registration.RegistrationConfig;

RegistrationConfig.builder()
//  .connection(SSHProvisionerConnection|WinrmProvisionerConnection)
//  .count(java.lang.Number|TerraformCount)
//  .dependsOn(java.util.List<ITerraformDependable>)
//  .forEach(ITerraformIterator)
//  .lifecycle(TerraformResourceLifecycle)
//  .provider(TerraformProvider)
//  .provisioners(java.util.List<FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner>)
//  .accountKeyAlgorithm(java.lang.String)
//  .accountKeyEcdsaCurve(java.lang.String)
//  .accountKeyPem(java.lang.String)
//  .accountKeyRsaBits(java.lang.Number)
//  .emailAddress(java.lang.String)
//  .externalAccountBinding(RegistrationExternalAccountBinding)
//  .id(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationConfig.property.connection">connection</a></code> | <code>io.cdktn.cdktn.SSHProvisionerConnection\|io.cdktn.cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationConfig.property.count">count</a></code> | <code>java.lang.Number\|io.cdktn.cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationConfig.property.dependsOn">dependsOn</a></code> | <code>java.util.List<io.cdktn.cdktn.ITerraformDependable></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationConfig.property.forEach">forEach</a></code> | <code>io.cdktn.cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationConfig.property.lifecycle">lifecycle</a></code> | <code>io.cdktn.cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationConfig.property.provider">provider</a></code> | <code>io.cdktn.cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationConfig.property.provisioners">provisioners</a></code> | <code>java.util.List<io.cdktn.cdktn.FileProvisioner\|io.cdktn.cdktn.LocalExecProvisioner\|io.cdktn.cdktn.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationConfig.property.accountKeyAlgorithm">accountKeyAlgorithm</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration#account_key_algorithm Registration#account_key_algorithm}. |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationConfig.property.accountKeyEcdsaCurve">accountKeyEcdsaCurve</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration#account_key_ecdsa_curve Registration#account_key_ecdsa_curve}. |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationConfig.property.accountKeyPem">accountKeyPem</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration#account_key_pem Registration#account_key_pem}. |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationConfig.property.accountKeyRsaBits">accountKeyRsaBits</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration#account_key_rsa_bits Registration#account_key_rsa_bits}. |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationConfig.property.emailAddress">emailAddress</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration#email_address Registration#email_address}. |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationConfig.property.externalAccountBinding">externalAccountBinding</a></code> | <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBinding">RegistrationExternalAccountBinding</a></code> | external_account_binding block. |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationConfig.property.id">id</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration#id Registration#id}. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-acme.registration.RegistrationConfig.property.connection"></a>

```java
public SSHProvisionerConnection|WinrmProvisionerConnection getConnection();
```

- *Type:* io.cdktn.cdktn.SSHProvisionerConnection|io.cdktn.cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-acme.registration.RegistrationConfig.property.count"></a>

```java
public java.lang.Number|TerraformCount getCount();
```

- *Type:* java.lang.Number|io.cdktn.cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-acme.registration.RegistrationConfig.property.dependsOn"></a>

```java
public java.util.List<ITerraformDependable> getDependsOn();
```

- *Type:* java.util.List<io.cdktn.cdktn.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-acme.registration.RegistrationConfig.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* io.cdktn.cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-acme.registration.RegistrationConfig.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* io.cdktn.cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-acme.registration.RegistrationConfig.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* io.cdktn.cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-acme.registration.RegistrationConfig.property.provisioners"></a>

```java
public java.util.List<FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner> getProvisioners();
```

- *Type:* java.util.List<io.cdktn.cdktn.FileProvisioner|io.cdktn.cdktn.LocalExecProvisioner|io.cdktn.cdktn.RemoteExecProvisioner>

---

##### `accountKeyAlgorithm`<sup>Optional</sup> <a name="accountKeyAlgorithm" id="@cdktn/provider-acme.registration.RegistrationConfig.property.accountKeyAlgorithm"></a>

```java
public java.lang.String getAccountKeyAlgorithm();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration#account_key_algorithm Registration#account_key_algorithm}.

---

##### `accountKeyEcdsaCurve`<sup>Optional</sup> <a name="accountKeyEcdsaCurve" id="@cdktn/provider-acme.registration.RegistrationConfig.property.accountKeyEcdsaCurve"></a>

```java
public java.lang.String getAccountKeyEcdsaCurve();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration#account_key_ecdsa_curve Registration#account_key_ecdsa_curve}.

---

##### `accountKeyPem`<sup>Optional</sup> <a name="accountKeyPem" id="@cdktn/provider-acme.registration.RegistrationConfig.property.accountKeyPem"></a>

```java
public java.lang.String getAccountKeyPem();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration#account_key_pem Registration#account_key_pem}.

---

##### `accountKeyRsaBits`<sup>Optional</sup> <a name="accountKeyRsaBits" id="@cdktn/provider-acme.registration.RegistrationConfig.property.accountKeyRsaBits"></a>

```java
public java.lang.Number getAccountKeyRsaBits();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration#account_key_rsa_bits Registration#account_key_rsa_bits}.

---

##### `emailAddress`<sup>Optional</sup> <a name="emailAddress" id="@cdktn/provider-acme.registration.RegistrationConfig.property.emailAddress"></a>

```java
public java.lang.String getEmailAddress();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration#email_address Registration#email_address}.

---

##### `externalAccountBinding`<sup>Optional</sup> <a name="externalAccountBinding" id="@cdktn/provider-acme.registration.RegistrationConfig.property.externalAccountBinding"></a>

```java
public RegistrationExternalAccountBinding getExternalAccountBinding();
```

- *Type:* <a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBinding">RegistrationExternalAccountBinding</a>

external_account_binding block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration#external_account_binding Registration#external_account_binding}

---

##### `id`<sup>Optional</sup> <a name="id" id="@cdktn/provider-acme.registration.RegistrationConfig.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration#id Registration#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

### RegistrationExternalAccountBinding <a name="RegistrationExternalAccountBinding" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBinding"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBinding.Initializer"></a>

```java
import io.cdktn.providers.acme.registration.RegistrationExternalAccountBinding;

RegistrationExternalAccountBinding.builder()
    .hmacBase64(java.lang.String)
    .keyId(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBinding.property.hmacBase64">hmacBase64</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration#hmac_base64 Registration#hmac_base64}. |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBinding.property.keyId">keyId</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration#key_id Registration#key_id}. |

---

##### `hmacBase64`<sup>Required</sup> <a name="hmacBase64" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBinding.property.hmacBase64"></a>

```java
public java.lang.String getHmacBase64();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration#hmac_base64 Registration#hmac_base64}.

---

##### `keyId`<sup>Required</sup> <a name="keyId" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBinding.property.keyId"></a>

```java
public java.lang.String getKeyId();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.48.3/docs/resources/registration#key_id Registration#key_id}.

---

## Classes <a name="Classes" id="Classes"></a>

### RegistrationExternalAccountBindingOutputReference <a name="RegistrationExternalAccountBindingOutputReference" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.Initializer"></a>

```java
import io.cdktn.providers.acme.registration.RegistrationExternalAccountBindingOutputReference;

new RegistrationExternalAccountBindingOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.hmacBase64Input">hmacBase64Input</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.keyIdInput">keyIdInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.hmacBase64">hmacBase64</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.keyId">keyId</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.internalValue">internalValue</a></code> | <code><a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBinding">RegistrationExternalAccountBinding</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `hmacBase64Input`<sup>Optional</sup> <a name="hmacBase64Input" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.hmacBase64Input"></a>

```java
public java.lang.String getHmacBase64Input();
```

- *Type:* java.lang.String

---

##### `keyIdInput`<sup>Optional</sup> <a name="keyIdInput" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.keyIdInput"></a>

```java
public java.lang.String getKeyIdInput();
```

- *Type:* java.lang.String

---

##### `hmacBase64`<sup>Required</sup> <a name="hmacBase64" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.hmacBase64"></a>

```java
public java.lang.String getHmacBase64();
```

- *Type:* java.lang.String

---

##### `keyId`<sup>Required</sup> <a name="keyId" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.keyId"></a>

```java
public java.lang.String getKeyId();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-acme.registration.RegistrationExternalAccountBindingOutputReference.property.internalValue"></a>

```java
public RegistrationExternalAccountBinding getInternalValue();
```

- *Type:* <a href="#@cdktn/provider-acme.registration.RegistrationExternalAccountBinding">RegistrationExternalAccountBinding</a>

---



