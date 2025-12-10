# `certificate` Submodule <a name="`certificate` Submodule" id="@cdktf/provider-acme.certificate"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### Certificate <a name="Certificate" id="@cdktf/provider-acme.certificate.Certificate"></a>

Represents a {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate acme_certificate}.

#### Initializers <a name="Initializers" id="@cdktf/provider-acme.certificate.Certificate.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-acme-go/acme/v12/certificate"

certificate.NewCertificate(scope Construct, id *string, config CertificateConfig) Certificate
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.Initializer.parameter.scope">scope</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.Initializer.parameter.id">id</a></code> | <code>*string</code> | The scoped construct ID. |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.Initializer.parameter.config">config</a></code> | <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig">CertificateConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktf/provider-acme.certificate.Certificate.Initializer.parameter.scope"></a>

- *Type:* github.com/aws/constructs-go/constructs/v10.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-acme.certificate.Certificate.Initializer.parameter.id"></a>

- *Type:* *string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="config" id="@cdktf/provider-acme.certificate.Certificate.Initializer.parameter.config"></a>

- *Type:* <a href="#@cdktf/provider-acme.certificate.CertificateConfig">CertificateConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.toString">ToString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.addOverride">AddOverride</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.overrideLogicalId">OverrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.resetOverrideLogicalId">ResetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.toHclTerraform">ToHclTerraform</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.toMetadata">ToMetadata</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.toTerraform">ToTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.addMoveTarget">AddMoveTarget</a></code> | Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move. |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.hasResourceMove">HasResourceMove</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.importFrom">ImportFrom</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.moveFromId">MoveFromId</a></code> | Move the resource corresponding to "id" to this resource. |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.moveTo">MoveTo</a></code> | Moves this resource to the target resource given by moveTarget. |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.moveToId">MoveToId</a></code> | Moves this resource to the resource corresponding to "id". |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.putDnsChallenge">PutDnsChallenge</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.putHttpChallenge">PutHttpChallenge</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.putHttpMemcachedChallenge">PutHttpMemcachedChallenge</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.putHttpS3Challenge">PutHttpS3Challenge</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.putHttpWebrootChallenge">PutHttpWebrootChallenge</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.putTlsChallenge">PutTlsChallenge</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.resetCertificateP12Password">ResetCertificateP12Password</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.resetCertificateRequestPem">ResetCertificateRequestPem</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.resetCertTimeout">ResetCertTimeout</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.resetCommonName">ResetCommonName</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.resetDisableCompletePropagation">ResetDisableCompletePropagation</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.resetDnsChallenge">ResetDnsChallenge</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.resetHttpChallenge">ResetHttpChallenge</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.resetHttpMemcachedChallenge">ResetHttpMemcachedChallenge</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.resetHttpS3Challenge">ResetHttpS3Challenge</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.resetHttpWebrootChallenge">ResetHttpWebrootChallenge</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.resetId">ResetId</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.resetKeyType">ResetKeyType</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.resetMinDaysRemaining">ResetMinDaysRemaining</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.resetMustStaple">ResetMustStaple</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.resetPreCheckDelay">ResetPreCheckDelay</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.resetPreferredChain">ResetPreferredChain</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.resetProfile">ResetProfile</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.resetRecursiveNameservers">ResetRecursiveNameservers</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.resetRenewalInfoIgnoreRetryAfter">ResetRenewalInfoIgnoreRetryAfter</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.resetRenewalInfoMaxSleep">ResetRenewalInfoMaxSleep</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.resetRevokeCertificateOnDestroy">ResetRevokeCertificateOnDestroy</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.resetRevokeCertificateReason">ResetRevokeCertificateReason</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.resetSubjectAlternativeNames">ResetSubjectAlternativeNames</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.resetTlsChallenge">ResetTlsChallenge</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.resetUseRenewalInfo">ResetUseRenewalInfo</a></code> | *No description.* |

---

##### `ToString` <a name="ToString" id="@cdktf/provider-acme.certificate.Certificate.toString"></a>

```go
func ToString() *string
```

Returns a string representation of this construct.

##### `AddOverride` <a name="AddOverride" id="@cdktf/provider-acme.certificate.Certificate.addOverride"></a>

```go
func AddOverride(path *string, value interface{})
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktf/provider-acme.certificate.Certificate.addOverride.parameter.path"></a>

- *Type:* *string

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-acme.certificate.Certificate.addOverride.parameter.value"></a>

- *Type:* interface{}

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="@cdktf/provider-acme.certificate.Certificate.overrideLogicalId"></a>

```go
func OverrideLogicalId(newLogicalId *string)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@cdktf/provider-acme.certificate.Certificate.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* *string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="@cdktf/provider-acme.certificate.Certificate.resetOverrideLogicalId"></a>

```go
func ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToHclTerraform` <a name="ToHclTerraform" id="@cdktf/provider-acme.certificate.Certificate.toHclTerraform"></a>

```go
func ToHclTerraform() interface{}
```

##### `ToMetadata` <a name="ToMetadata" id="@cdktf/provider-acme.certificate.Certificate.toMetadata"></a>

```go
func ToMetadata() interface{}
```

##### `ToTerraform` <a name="ToTerraform" id="@cdktf/provider-acme.certificate.Certificate.toTerraform"></a>

```go
func ToTerraform() interface{}
```

Adds this resource to the terraform JSON output.

##### `AddMoveTarget` <a name="AddMoveTarget" id="@cdktf/provider-acme.certificate.Certificate.addMoveTarget"></a>

```go
func AddMoveTarget(moveTarget *string)
```

Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktf/provider-acme.certificate.Certificate.addMoveTarget.parameter.moveTarget"></a>

- *Type:* *string

The string move target that will correspond to this resource.

---

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktf/provider-acme.certificate.Certificate.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.Certificate.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktf/provider-acme.certificate.Certificate.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.Certificate.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktf/provider-acme.certificate.Certificate.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.Certificate.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktf/provider-acme.certificate.Certificate.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.Certificate.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktf/provider-acme.certificate.Certificate.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.Certificate.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktf/provider-acme.certificate.Certificate.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.Certificate.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktf/provider-acme.certificate.Certificate.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.Certificate.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktf/provider-acme.certificate.Certificate.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.Certificate.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktf/provider-acme.certificate.Certificate.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.Certificate.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `HasResourceMove` <a name="HasResourceMove" id="@cdktf/provider-acme.certificate.Certificate.hasResourceMove"></a>

```go
func HasResourceMove() interface{}
```

##### `ImportFrom` <a name="ImportFrom" id="@cdktf/provider-acme.certificate.Certificate.importFrom"></a>

```go
func ImportFrom(id *string, provider TerraformProvider)
```

###### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-acme.certificate.Certificate.importFrom.parameter.id"></a>

- *Type:* *string

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-acme.certificate.Certificate.importFrom.parameter.provider"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktf/provider-acme.certificate.Certificate.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.Certificate.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `MoveFromId` <a name="MoveFromId" id="@cdktf/provider-acme.certificate.Certificate.moveFromId"></a>

```go
func MoveFromId(id *string)
```

Move the resource corresponding to "id" to this resource.

Note that the resource being moved from must be marked as moved using it's instance function.

###### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-acme.certificate.Certificate.moveFromId.parameter.id"></a>

- *Type:* *string

Full id of resource being moved from, e.g. "aws_s3_bucket.example".

---

##### `MoveTo` <a name="MoveTo" id="@cdktf/provider-acme.certificate.Certificate.moveTo"></a>

```go
func MoveTo(moveTarget *string, index interface{})
```

Moves this resource to the target resource given by moveTarget.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktf/provider-acme.certificate.Certificate.moveTo.parameter.moveTarget"></a>

- *Type:* *string

The previously set user defined string set by .addMoveTarget() corresponding to the resource to move to.

---

###### `index`<sup>Optional</sup> <a name="index" id="@cdktf/provider-acme.certificate.Certificate.moveTo.parameter.index"></a>

- *Type:* interface{}

Optional The index corresponding to the key the resource is to appear in the foreach of a resource to move to.

---

##### `MoveToId` <a name="MoveToId" id="@cdktf/provider-acme.certificate.Certificate.moveToId"></a>

```go
func MoveToId(id *string)
```

Moves this resource to the resource corresponding to "id".

###### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-acme.certificate.Certificate.moveToId.parameter.id"></a>

- *Type:* *string

Full id of resource to move to, e.g. "aws_s3_bucket.example".

---

##### `PutDnsChallenge` <a name="PutDnsChallenge" id="@cdktf/provider-acme.certificate.Certificate.putDnsChallenge"></a>

```go
func PutDnsChallenge(value interface{})
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-acme.certificate.Certificate.putDnsChallenge.parameter.value"></a>

- *Type:* interface{}

---

##### `PutHttpChallenge` <a name="PutHttpChallenge" id="@cdktf/provider-acme.certificate.Certificate.putHttpChallenge"></a>

```go
func PutHttpChallenge(value CertificateHttpChallenge)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-acme.certificate.Certificate.putHttpChallenge.parameter.value"></a>

- *Type:* <a href="#@cdktf/provider-acme.certificate.CertificateHttpChallenge">CertificateHttpChallenge</a>

---

##### `PutHttpMemcachedChallenge` <a name="PutHttpMemcachedChallenge" id="@cdktf/provider-acme.certificate.Certificate.putHttpMemcachedChallenge"></a>

```go
func PutHttpMemcachedChallenge(value CertificateHttpMemcachedChallenge)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-acme.certificate.Certificate.putHttpMemcachedChallenge.parameter.value"></a>

- *Type:* <a href="#@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallenge">CertificateHttpMemcachedChallenge</a>

---

##### `PutHttpS3Challenge` <a name="PutHttpS3Challenge" id="@cdktf/provider-acme.certificate.Certificate.putHttpS3Challenge"></a>

```go
func PutHttpS3Challenge(value CertificateHttpS3Challenge)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-acme.certificate.Certificate.putHttpS3Challenge.parameter.value"></a>

- *Type:* <a href="#@cdktf/provider-acme.certificate.CertificateHttpS3Challenge">CertificateHttpS3Challenge</a>

---

##### `PutHttpWebrootChallenge` <a name="PutHttpWebrootChallenge" id="@cdktf/provider-acme.certificate.Certificate.putHttpWebrootChallenge"></a>

```go
func PutHttpWebrootChallenge(value CertificateHttpWebrootChallenge)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-acme.certificate.Certificate.putHttpWebrootChallenge.parameter.value"></a>

- *Type:* <a href="#@cdktf/provider-acme.certificate.CertificateHttpWebrootChallenge">CertificateHttpWebrootChallenge</a>

---

##### `PutTlsChallenge` <a name="PutTlsChallenge" id="@cdktf/provider-acme.certificate.Certificate.putTlsChallenge"></a>

```go
func PutTlsChallenge(value CertificateTlsChallenge)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-acme.certificate.Certificate.putTlsChallenge.parameter.value"></a>

- *Type:* <a href="#@cdktf/provider-acme.certificate.CertificateTlsChallenge">CertificateTlsChallenge</a>

---

##### `ResetCertificateP12Password` <a name="ResetCertificateP12Password" id="@cdktf/provider-acme.certificate.Certificate.resetCertificateP12Password"></a>

```go
func ResetCertificateP12Password()
```

##### `ResetCertificateRequestPem` <a name="ResetCertificateRequestPem" id="@cdktf/provider-acme.certificate.Certificate.resetCertificateRequestPem"></a>

```go
func ResetCertificateRequestPem()
```

##### `ResetCertTimeout` <a name="ResetCertTimeout" id="@cdktf/provider-acme.certificate.Certificate.resetCertTimeout"></a>

```go
func ResetCertTimeout()
```

##### `ResetCommonName` <a name="ResetCommonName" id="@cdktf/provider-acme.certificate.Certificate.resetCommonName"></a>

```go
func ResetCommonName()
```

##### `ResetDisableCompletePropagation` <a name="ResetDisableCompletePropagation" id="@cdktf/provider-acme.certificate.Certificate.resetDisableCompletePropagation"></a>

```go
func ResetDisableCompletePropagation()
```

##### `ResetDnsChallenge` <a name="ResetDnsChallenge" id="@cdktf/provider-acme.certificate.Certificate.resetDnsChallenge"></a>

```go
func ResetDnsChallenge()
```

##### `ResetHttpChallenge` <a name="ResetHttpChallenge" id="@cdktf/provider-acme.certificate.Certificate.resetHttpChallenge"></a>

```go
func ResetHttpChallenge()
```

##### `ResetHttpMemcachedChallenge` <a name="ResetHttpMemcachedChallenge" id="@cdktf/provider-acme.certificate.Certificate.resetHttpMemcachedChallenge"></a>

```go
func ResetHttpMemcachedChallenge()
```

##### `ResetHttpS3Challenge` <a name="ResetHttpS3Challenge" id="@cdktf/provider-acme.certificate.Certificate.resetHttpS3Challenge"></a>

```go
func ResetHttpS3Challenge()
```

##### `ResetHttpWebrootChallenge` <a name="ResetHttpWebrootChallenge" id="@cdktf/provider-acme.certificate.Certificate.resetHttpWebrootChallenge"></a>

```go
func ResetHttpWebrootChallenge()
```

##### `ResetId` <a name="ResetId" id="@cdktf/provider-acme.certificate.Certificate.resetId"></a>

```go
func ResetId()
```

##### `ResetKeyType` <a name="ResetKeyType" id="@cdktf/provider-acme.certificate.Certificate.resetKeyType"></a>

```go
func ResetKeyType()
```

##### `ResetMinDaysRemaining` <a name="ResetMinDaysRemaining" id="@cdktf/provider-acme.certificate.Certificate.resetMinDaysRemaining"></a>

```go
func ResetMinDaysRemaining()
```

##### `ResetMustStaple` <a name="ResetMustStaple" id="@cdktf/provider-acme.certificate.Certificate.resetMustStaple"></a>

```go
func ResetMustStaple()
```

##### `ResetPreCheckDelay` <a name="ResetPreCheckDelay" id="@cdktf/provider-acme.certificate.Certificate.resetPreCheckDelay"></a>

```go
func ResetPreCheckDelay()
```

##### `ResetPreferredChain` <a name="ResetPreferredChain" id="@cdktf/provider-acme.certificate.Certificate.resetPreferredChain"></a>

```go
func ResetPreferredChain()
```

##### `ResetProfile` <a name="ResetProfile" id="@cdktf/provider-acme.certificate.Certificate.resetProfile"></a>

```go
func ResetProfile()
```

##### `ResetRecursiveNameservers` <a name="ResetRecursiveNameservers" id="@cdktf/provider-acme.certificate.Certificate.resetRecursiveNameservers"></a>

```go
func ResetRecursiveNameservers()
```

##### `ResetRenewalInfoIgnoreRetryAfter` <a name="ResetRenewalInfoIgnoreRetryAfter" id="@cdktf/provider-acme.certificate.Certificate.resetRenewalInfoIgnoreRetryAfter"></a>

```go
func ResetRenewalInfoIgnoreRetryAfter()
```

##### `ResetRenewalInfoMaxSleep` <a name="ResetRenewalInfoMaxSleep" id="@cdktf/provider-acme.certificate.Certificate.resetRenewalInfoMaxSleep"></a>

```go
func ResetRenewalInfoMaxSleep()
```

##### `ResetRevokeCertificateOnDestroy` <a name="ResetRevokeCertificateOnDestroy" id="@cdktf/provider-acme.certificate.Certificate.resetRevokeCertificateOnDestroy"></a>

```go
func ResetRevokeCertificateOnDestroy()
```

##### `ResetRevokeCertificateReason` <a name="ResetRevokeCertificateReason" id="@cdktf/provider-acme.certificate.Certificate.resetRevokeCertificateReason"></a>

```go
func ResetRevokeCertificateReason()
```

##### `ResetSubjectAlternativeNames` <a name="ResetSubjectAlternativeNames" id="@cdktf/provider-acme.certificate.Certificate.resetSubjectAlternativeNames"></a>

```go
func ResetSubjectAlternativeNames()
```

##### `ResetTlsChallenge` <a name="ResetTlsChallenge" id="@cdktf/provider-acme.certificate.Certificate.resetTlsChallenge"></a>

```go
func ResetTlsChallenge()
```

##### `ResetUseRenewalInfo` <a name="ResetUseRenewalInfo" id="@cdktf/provider-acme.certificate.Certificate.resetUseRenewalInfo"></a>

```go
func ResetUseRenewalInfo()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.isConstruct">IsConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.isTerraformElement">IsTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.isTerraformResource">IsTerraformResource</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.generateConfigForImport">GenerateConfigForImport</a></code> | Generates CDKTF code for importing a Certificate resource upon running "cdktf plan <stack-name>". |

---

##### `IsConstruct` <a name="IsConstruct" id="@cdktf/provider-acme.certificate.Certificate.isConstruct"></a>

```go
import "github.com/cdktf/cdktf-provider-acme-go/acme/v12/certificate"

certificate.Certificate_IsConstruct(x interface{}) *bool
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

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-acme.certificate.Certificate.isConstruct.parameter.x"></a>

- *Type:* interface{}

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="@cdktf/provider-acme.certificate.Certificate.isTerraformElement"></a>

```go
import "github.com/cdktf/cdktf-provider-acme-go/acme/v12/certificate"

certificate.Certificate_IsTerraformElement(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-acme.certificate.Certificate.isTerraformElement.parameter.x"></a>

- *Type:* interface{}

---

##### `IsTerraformResource` <a name="IsTerraformResource" id="@cdktf/provider-acme.certificate.Certificate.isTerraformResource"></a>

```go
import "github.com/cdktf/cdktf-provider-acme-go/acme/v12/certificate"

certificate.Certificate_IsTerraformResource(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-acme.certificate.Certificate.isTerraformResource.parameter.x"></a>

- *Type:* interface{}

---

##### `GenerateConfigForImport` <a name="GenerateConfigForImport" id="@cdktf/provider-acme.certificate.Certificate.generateConfigForImport"></a>

```go
import "github.com/cdktf/cdktf-provider-acme-go/acme/v12/certificate"

certificate.Certificate_GenerateConfigForImport(scope Construct, importToId *string, importFromId *string, provider TerraformProvider) ImportableResource
```

Generates CDKTF code for importing a Certificate resource upon running "cdktf plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktf/provider-acme.certificate.Certificate.generateConfigForImport.parameter.scope"></a>

- *Type:* github.com/aws/constructs-go/constructs/v10.Construct

The scope in which to define this construct.

---

###### `importToId`<sup>Required</sup> <a name="importToId" id="@cdktf/provider-acme.certificate.Certificate.generateConfigForImport.parameter.importToId"></a>

- *Type:* *string

The construct id used in the generated config for the Certificate to import.

---

###### `importFromId`<sup>Required</sup> <a name="importFromId" id="@cdktf/provider-acme.certificate.Certificate.generateConfigForImport.parameter.importFromId"></a>

- *Type:* *string

The id of the existing Certificate that should be imported.

Refer to the {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#import import section} in the documentation of this resource for the id to use

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-acme.certificate.Certificate.generateConfigForImport.parameter.provider"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

? Optional instance of the provider where the Certificate to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.node">Node</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Node</code> | The tree node. |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.cdktfStack">CdktfStack</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>*map[string]interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.terraformResourceType">TerraformResourceType</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.connection">Connection</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.count">Count</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.dependsOn">DependsOn</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.forEach">ForEach</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.lifecycle">Lifecycle</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.provider">Provider</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.provisioners">Provisioners</a></code> | <code>*[]interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.certificateDomain">CertificateDomain</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.certificateNotAfter">CertificateNotAfter</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.certificateP12">CertificateP12</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.certificatePem">CertificatePem</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.certificateSerial">CertificateSerial</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.certificateUrl">CertificateUrl</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.dnsChallenge">DnsChallenge</a></code> | <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeList">CertificateDnsChallengeList</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.httpChallenge">HttpChallenge</a></code> | <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference">CertificateHttpChallengeOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.httpMemcachedChallenge">HttpMemcachedChallenge</a></code> | <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference">CertificateHttpMemcachedChallengeOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.httpS3Challenge">HttpS3Challenge</a></code> | <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference">CertificateHttpS3ChallengeOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.httpWebrootChallenge">HttpWebrootChallenge</a></code> | <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference">CertificateHttpWebrootChallengeOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.issuerPem">IssuerPem</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.privateKeyPem">PrivateKeyPem</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.renewalInfoExplanationUrl">RenewalInfoExplanationUrl</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.renewalInfoRetryAfter">RenewalInfoRetryAfter</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.renewalInfoWindowEnd">RenewalInfoWindowEnd</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.renewalInfoWindowSelected">RenewalInfoWindowSelected</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.renewalInfoWindowStart">RenewalInfoWindowStart</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.tlsChallenge">TlsChallenge</a></code> | <code><a href="#@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference">CertificateTlsChallengeOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.accountKeyPemInput">AccountKeyPemInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.certificateP12PasswordInput">CertificateP12PasswordInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.certificateRequestPemInput">CertificateRequestPemInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.certTimeoutInput">CertTimeoutInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.commonNameInput">CommonNameInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.disableCompletePropagationInput">DisableCompletePropagationInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.dnsChallengeInput">DnsChallengeInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.httpChallengeInput">HttpChallengeInput</a></code> | <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpChallenge">CertificateHttpChallenge</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.httpMemcachedChallengeInput">HttpMemcachedChallengeInput</a></code> | <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallenge">CertificateHttpMemcachedChallenge</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.httpS3ChallengeInput">HttpS3ChallengeInput</a></code> | <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpS3Challenge">CertificateHttpS3Challenge</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.httpWebrootChallengeInput">HttpWebrootChallengeInput</a></code> | <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpWebrootChallenge">CertificateHttpWebrootChallenge</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.idInput">IdInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.keyTypeInput">KeyTypeInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.minDaysRemainingInput">MinDaysRemainingInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.mustStapleInput">MustStapleInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.preCheckDelayInput">PreCheckDelayInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.preferredChainInput">PreferredChainInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.profileInput">ProfileInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.recursiveNameserversInput">RecursiveNameserversInput</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.renewalInfoIgnoreRetryAfterInput">RenewalInfoIgnoreRetryAfterInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.renewalInfoMaxSleepInput">RenewalInfoMaxSleepInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.revokeCertificateOnDestroyInput">RevokeCertificateOnDestroyInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.revokeCertificateReasonInput">RevokeCertificateReasonInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.subjectAlternativeNamesInput">SubjectAlternativeNamesInput</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.tlsChallengeInput">TlsChallengeInput</a></code> | <code><a href="#@cdktf/provider-acme.certificate.CertificateTlsChallenge">CertificateTlsChallenge</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.useRenewalInfoInput">UseRenewalInfoInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.accountKeyPem">AccountKeyPem</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.certificateP12Password">CertificateP12Password</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.certificateRequestPem">CertificateRequestPem</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.certTimeout">CertTimeout</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.commonName">CommonName</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.disableCompletePropagation">DisableCompletePropagation</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.id">Id</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.keyType">KeyType</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.minDaysRemaining">MinDaysRemaining</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.mustStaple">MustStaple</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.preCheckDelay">PreCheckDelay</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.preferredChain">PreferredChain</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.profile">Profile</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.recursiveNameservers">RecursiveNameservers</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.renewalInfoIgnoreRetryAfter">RenewalInfoIgnoreRetryAfter</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.renewalInfoMaxSleep">RenewalInfoMaxSleep</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.revokeCertificateOnDestroy">RevokeCertificateOnDestroy</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.revokeCertificateReason">RevokeCertificateReason</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.subjectAlternativeNames">SubjectAlternativeNames</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.useRenewalInfo">UseRenewalInfo</a></code> | <code>interface{}</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="@cdktf/provider-acme.certificate.Certificate.property.node"></a>

```go
func Node() Node
```

- *Type:* github.com/aws/constructs-go/constructs/v10.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="@cdktf/provider-acme.certificate.Certificate.property.cdktfStack"></a>

```go
func CdktfStack() TerraformStack
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-acme.certificate.Certificate.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="@cdktf/provider-acme.certificate.Certificate.property.friendlyUniqueId"></a>

```go
func FriendlyUniqueId() *string
```

- *Type:* *string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="@cdktf/provider-acme.certificate.Certificate.property.terraformMetaArguments"></a>

```go
func TerraformMetaArguments() *map[string]interface{}
```

- *Type:* *map[string]interface{}

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="@cdktf/provider-acme.certificate.Certificate.property.terraformResourceType"></a>

```go
func TerraformResourceType() *string
```

- *Type:* *string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="@cdktf/provider-acme.certificate.Certificate.property.terraformGeneratorMetadata"></a>

```go
func TerraformGeneratorMetadata() TerraformProviderGeneratorMetadata
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProviderGeneratorMetadata

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktf/provider-acme.certificate.Certificate.property.connection"></a>

```go
func Connection() interface{}
```

- *Type:* interface{}

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktf/provider-acme.certificate.Certificate.property.count"></a>

```go
func Count() interface{}
```

- *Type:* interface{}

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktf/provider-acme.certificate.Certificate.property.dependsOn"></a>

```go
func DependsOn() *[]*string
```

- *Type:* *[]*string

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktf/provider-acme.certificate.Certificate.property.forEach"></a>

```go
func ForEach() ITerraformIterator
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktf/provider-acme.certificate.Certificate.property.lifecycle"></a>

```go
func Lifecycle() TerraformResourceLifecycle
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktf/provider-acme.certificate.Certificate.property.provider"></a>

```go
func Provider() TerraformProvider
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktf/provider-acme.certificate.Certificate.property.provisioners"></a>

```go
func Provisioners() *[]interface{}
```

- *Type:* *[]interface{}

---

##### `CertificateDomain`<sup>Required</sup> <a name="CertificateDomain" id="@cdktf/provider-acme.certificate.Certificate.property.certificateDomain"></a>

```go
func CertificateDomain() *string
```

- *Type:* *string

---

##### `CertificateNotAfter`<sup>Required</sup> <a name="CertificateNotAfter" id="@cdktf/provider-acme.certificate.Certificate.property.certificateNotAfter"></a>

```go
func CertificateNotAfter() *string
```

- *Type:* *string

---

##### `CertificateP12`<sup>Required</sup> <a name="CertificateP12" id="@cdktf/provider-acme.certificate.Certificate.property.certificateP12"></a>

```go
func CertificateP12() *string
```

- *Type:* *string

---

##### `CertificatePem`<sup>Required</sup> <a name="CertificatePem" id="@cdktf/provider-acme.certificate.Certificate.property.certificatePem"></a>

```go
func CertificatePem() *string
```

- *Type:* *string

---

##### `CertificateSerial`<sup>Required</sup> <a name="CertificateSerial" id="@cdktf/provider-acme.certificate.Certificate.property.certificateSerial"></a>

```go
func CertificateSerial() *string
```

- *Type:* *string

---

##### `CertificateUrl`<sup>Required</sup> <a name="CertificateUrl" id="@cdktf/provider-acme.certificate.Certificate.property.certificateUrl"></a>

```go
func CertificateUrl() *string
```

- *Type:* *string

---

##### `DnsChallenge`<sup>Required</sup> <a name="DnsChallenge" id="@cdktf/provider-acme.certificate.Certificate.property.dnsChallenge"></a>

```go
func DnsChallenge() CertificateDnsChallengeList
```

- *Type:* <a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeList">CertificateDnsChallengeList</a>

---

##### `HttpChallenge`<sup>Required</sup> <a name="HttpChallenge" id="@cdktf/provider-acme.certificate.Certificate.property.httpChallenge"></a>

```go
func HttpChallenge() CertificateHttpChallengeOutputReference
```

- *Type:* <a href="#@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference">CertificateHttpChallengeOutputReference</a>

---

##### `HttpMemcachedChallenge`<sup>Required</sup> <a name="HttpMemcachedChallenge" id="@cdktf/provider-acme.certificate.Certificate.property.httpMemcachedChallenge"></a>

```go
func HttpMemcachedChallenge() CertificateHttpMemcachedChallengeOutputReference
```

- *Type:* <a href="#@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference">CertificateHttpMemcachedChallengeOutputReference</a>

---

##### `HttpS3Challenge`<sup>Required</sup> <a name="HttpS3Challenge" id="@cdktf/provider-acme.certificate.Certificate.property.httpS3Challenge"></a>

```go
func HttpS3Challenge() CertificateHttpS3ChallengeOutputReference
```

- *Type:* <a href="#@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference">CertificateHttpS3ChallengeOutputReference</a>

---

##### `HttpWebrootChallenge`<sup>Required</sup> <a name="HttpWebrootChallenge" id="@cdktf/provider-acme.certificate.Certificate.property.httpWebrootChallenge"></a>

```go
func HttpWebrootChallenge() CertificateHttpWebrootChallengeOutputReference
```

- *Type:* <a href="#@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference">CertificateHttpWebrootChallengeOutputReference</a>

---

##### `IssuerPem`<sup>Required</sup> <a name="IssuerPem" id="@cdktf/provider-acme.certificate.Certificate.property.issuerPem"></a>

```go
func IssuerPem() *string
```

- *Type:* *string

---

##### `PrivateKeyPem`<sup>Required</sup> <a name="PrivateKeyPem" id="@cdktf/provider-acme.certificate.Certificate.property.privateKeyPem"></a>

```go
func PrivateKeyPem() *string
```

- *Type:* *string

---

##### `RenewalInfoExplanationUrl`<sup>Required</sup> <a name="RenewalInfoExplanationUrl" id="@cdktf/provider-acme.certificate.Certificate.property.renewalInfoExplanationUrl"></a>

```go
func RenewalInfoExplanationUrl() *string
```

- *Type:* *string

---

##### `RenewalInfoRetryAfter`<sup>Required</sup> <a name="RenewalInfoRetryAfter" id="@cdktf/provider-acme.certificate.Certificate.property.renewalInfoRetryAfter"></a>

```go
func RenewalInfoRetryAfter() *string
```

- *Type:* *string

---

##### `RenewalInfoWindowEnd`<sup>Required</sup> <a name="RenewalInfoWindowEnd" id="@cdktf/provider-acme.certificate.Certificate.property.renewalInfoWindowEnd"></a>

```go
func RenewalInfoWindowEnd() *string
```

- *Type:* *string

---

##### `RenewalInfoWindowSelected`<sup>Required</sup> <a name="RenewalInfoWindowSelected" id="@cdktf/provider-acme.certificate.Certificate.property.renewalInfoWindowSelected"></a>

```go
func RenewalInfoWindowSelected() *string
```

- *Type:* *string

---

##### `RenewalInfoWindowStart`<sup>Required</sup> <a name="RenewalInfoWindowStart" id="@cdktf/provider-acme.certificate.Certificate.property.renewalInfoWindowStart"></a>

```go
func RenewalInfoWindowStart() *string
```

- *Type:* *string

---

##### `TlsChallenge`<sup>Required</sup> <a name="TlsChallenge" id="@cdktf/provider-acme.certificate.Certificate.property.tlsChallenge"></a>

```go
func TlsChallenge() CertificateTlsChallengeOutputReference
```

- *Type:* <a href="#@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference">CertificateTlsChallengeOutputReference</a>

---

##### `AccountKeyPemInput`<sup>Optional</sup> <a name="AccountKeyPemInput" id="@cdktf/provider-acme.certificate.Certificate.property.accountKeyPemInput"></a>

```go
func AccountKeyPemInput() *string
```

- *Type:* *string

---

##### `CertificateP12PasswordInput`<sup>Optional</sup> <a name="CertificateP12PasswordInput" id="@cdktf/provider-acme.certificate.Certificate.property.certificateP12PasswordInput"></a>

```go
func CertificateP12PasswordInput() *string
```

- *Type:* *string

---

##### `CertificateRequestPemInput`<sup>Optional</sup> <a name="CertificateRequestPemInput" id="@cdktf/provider-acme.certificate.Certificate.property.certificateRequestPemInput"></a>

```go
func CertificateRequestPemInput() *string
```

- *Type:* *string

---

##### `CertTimeoutInput`<sup>Optional</sup> <a name="CertTimeoutInput" id="@cdktf/provider-acme.certificate.Certificate.property.certTimeoutInput"></a>

```go
func CertTimeoutInput() *f64
```

- *Type:* *f64

---

##### `CommonNameInput`<sup>Optional</sup> <a name="CommonNameInput" id="@cdktf/provider-acme.certificate.Certificate.property.commonNameInput"></a>

```go
func CommonNameInput() *string
```

- *Type:* *string

---

##### `DisableCompletePropagationInput`<sup>Optional</sup> <a name="DisableCompletePropagationInput" id="@cdktf/provider-acme.certificate.Certificate.property.disableCompletePropagationInput"></a>

```go
func DisableCompletePropagationInput() interface{}
```

- *Type:* interface{}

---

##### `DnsChallengeInput`<sup>Optional</sup> <a name="DnsChallengeInput" id="@cdktf/provider-acme.certificate.Certificate.property.dnsChallengeInput"></a>

```go
func DnsChallengeInput() interface{}
```

- *Type:* interface{}

---

##### `HttpChallengeInput`<sup>Optional</sup> <a name="HttpChallengeInput" id="@cdktf/provider-acme.certificate.Certificate.property.httpChallengeInput"></a>

```go
func HttpChallengeInput() CertificateHttpChallenge
```

- *Type:* <a href="#@cdktf/provider-acme.certificate.CertificateHttpChallenge">CertificateHttpChallenge</a>

---

##### `HttpMemcachedChallengeInput`<sup>Optional</sup> <a name="HttpMemcachedChallengeInput" id="@cdktf/provider-acme.certificate.Certificate.property.httpMemcachedChallengeInput"></a>

```go
func HttpMemcachedChallengeInput() CertificateHttpMemcachedChallenge
```

- *Type:* <a href="#@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallenge">CertificateHttpMemcachedChallenge</a>

---

##### `HttpS3ChallengeInput`<sup>Optional</sup> <a name="HttpS3ChallengeInput" id="@cdktf/provider-acme.certificate.Certificate.property.httpS3ChallengeInput"></a>

```go
func HttpS3ChallengeInput() CertificateHttpS3Challenge
```

- *Type:* <a href="#@cdktf/provider-acme.certificate.CertificateHttpS3Challenge">CertificateHttpS3Challenge</a>

---

##### `HttpWebrootChallengeInput`<sup>Optional</sup> <a name="HttpWebrootChallengeInput" id="@cdktf/provider-acme.certificate.Certificate.property.httpWebrootChallengeInput"></a>

```go
func HttpWebrootChallengeInput() CertificateHttpWebrootChallenge
```

- *Type:* <a href="#@cdktf/provider-acme.certificate.CertificateHttpWebrootChallenge">CertificateHttpWebrootChallenge</a>

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="@cdktf/provider-acme.certificate.Certificate.property.idInput"></a>

```go
func IdInput() *string
```

- *Type:* *string

---

##### `KeyTypeInput`<sup>Optional</sup> <a name="KeyTypeInput" id="@cdktf/provider-acme.certificate.Certificate.property.keyTypeInput"></a>

```go
func KeyTypeInput() *string
```

- *Type:* *string

---

##### `MinDaysRemainingInput`<sup>Optional</sup> <a name="MinDaysRemainingInput" id="@cdktf/provider-acme.certificate.Certificate.property.minDaysRemainingInput"></a>

```go
func MinDaysRemainingInput() *f64
```

- *Type:* *f64

---

##### `MustStapleInput`<sup>Optional</sup> <a name="MustStapleInput" id="@cdktf/provider-acme.certificate.Certificate.property.mustStapleInput"></a>

```go
func MustStapleInput() interface{}
```

- *Type:* interface{}

---

##### `PreCheckDelayInput`<sup>Optional</sup> <a name="PreCheckDelayInput" id="@cdktf/provider-acme.certificate.Certificate.property.preCheckDelayInput"></a>

```go
func PreCheckDelayInput() *f64
```

- *Type:* *f64

---

##### `PreferredChainInput`<sup>Optional</sup> <a name="PreferredChainInput" id="@cdktf/provider-acme.certificate.Certificate.property.preferredChainInput"></a>

```go
func PreferredChainInput() *string
```

- *Type:* *string

---

##### `ProfileInput`<sup>Optional</sup> <a name="ProfileInput" id="@cdktf/provider-acme.certificate.Certificate.property.profileInput"></a>

```go
func ProfileInput() *string
```

- *Type:* *string

---

##### `RecursiveNameserversInput`<sup>Optional</sup> <a name="RecursiveNameserversInput" id="@cdktf/provider-acme.certificate.Certificate.property.recursiveNameserversInput"></a>

```go
func RecursiveNameserversInput() *[]*string
```

- *Type:* *[]*string

---

##### `RenewalInfoIgnoreRetryAfterInput`<sup>Optional</sup> <a name="RenewalInfoIgnoreRetryAfterInput" id="@cdktf/provider-acme.certificate.Certificate.property.renewalInfoIgnoreRetryAfterInput"></a>

```go
func RenewalInfoIgnoreRetryAfterInput() interface{}
```

- *Type:* interface{}

---

##### `RenewalInfoMaxSleepInput`<sup>Optional</sup> <a name="RenewalInfoMaxSleepInput" id="@cdktf/provider-acme.certificate.Certificate.property.renewalInfoMaxSleepInput"></a>

```go
func RenewalInfoMaxSleepInput() *f64
```

- *Type:* *f64

---

##### `RevokeCertificateOnDestroyInput`<sup>Optional</sup> <a name="RevokeCertificateOnDestroyInput" id="@cdktf/provider-acme.certificate.Certificate.property.revokeCertificateOnDestroyInput"></a>

```go
func RevokeCertificateOnDestroyInput() interface{}
```

- *Type:* interface{}

---

##### `RevokeCertificateReasonInput`<sup>Optional</sup> <a name="RevokeCertificateReasonInput" id="@cdktf/provider-acme.certificate.Certificate.property.revokeCertificateReasonInput"></a>

```go
func RevokeCertificateReasonInput() *string
```

- *Type:* *string

---

##### `SubjectAlternativeNamesInput`<sup>Optional</sup> <a name="SubjectAlternativeNamesInput" id="@cdktf/provider-acme.certificate.Certificate.property.subjectAlternativeNamesInput"></a>

```go
func SubjectAlternativeNamesInput() *[]*string
```

- *Type:* *[]*string

---

##### `TlsChallengeInput`<sup>Optional</sup> <a name="TlsChallengeInput" id="@cdktf/provider-acme.certificate.Certificate.property.tlsChallengeInput"></a>

```go
func TlsChallengeInput() CertificateTlsChallenge
```

- *Type:* <a href="#@cdktf/provider-acme.certificate.CertificateTlsChallenge">CertificateTlsChallenge</a>

---

##### `UseRenewalInfoInput`<sup>Optional</sup> <a name="UseRenewalInfoInput" id="@cdktf/provider-acme.certificate.Certificate.property.useRenewalInfoInput"></a>

```go
func UseRenewalInfoInput() interface{}
```

- *Type:* interface{}

---

##### `AccountKeyPem`<sup>Required</sup> <a name="AccountKeyPem" id="@cdktf/provider-acme.certificate.Certificate.property.accountKeyPem"></a>

```go
func AccountKeyPem() *string
```

- *Type:* *string

---

##### `CertificateP12Password`<sup>Required</sup> <a name="CertificateP12Password" id="@cdktf/provider-acme.certificate.Certificate.property.certificateP12Password"></a>

```go
func CertificateP12Password() *string
```

- *Type:* *string

---

##### `CertificateRequestPem`<sup>Required</sup> <a name="CertificateRequestPem" id="@cdktf/provider-acme.certificate.Certificate.property.certificateRequestPem"></a>

```go
func CertificateRequestPem() *string
```

- *Type:* *string

---

##### `CertTimeout`<sup>Required</sup> <a name="CertTimeout" id="@cdktf/provider-acme.certificate.Certificate.property.certTimeout"></a>

```go
func CertTimeout() *f64
```

- *Type:* *f64

---

##### `CommonName`<sup>Required</sup> <a name="CommonName" id="@cdktf/provider-acme.certificate.Certificate.property.commonName"></a>

```go
func CommonName() *string
```

- *Type:* *string

---

##### `DisableCompletePropagation`<sup>Required</sup> <a name="DisableCompletePropagation" id="@cdktf/provider-acme.certificate.Certificate.property.disableCompletePropagation"></a>

```go
func DisableCompletePropagation() interface{}
```

- *Type:* interface{}

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktf/provider-acme.certificate.Certificate.property.id"></a>

```go
func Id() *string
```

- *Type:* *string

---

##### `KeyType`<sup>Required</sup> <a name="KeyType" id="@cdktf/provider-acme.certificate.Certificate.property.keyType"></a>

```go
func KeyType() *string
```

- *Type:* *string

---

##### `MinDaysRemaining`<sup>Required</sup> <a name="MinDaysRemaining" id="@cdktf/provider-acme.certificate.Certificate.property.minDaysRemaining"></a>

```go
func MinDaysRemaining() *f64
```

- *Type:* *f64

---

##### `MustStaple`<sup>Required</sup> <a name="MustStaple" id="@cdktf/provider-acme.certificate.Certificate.property.mustStaple"></a>

```go
func MustStaple() interface{}
```

- *Type:* interface{}

---

##### `PreCheckDelay`<sup>Required</sup> <a name="PreCheckDelay" id="@cdktf/provider-acme.certificate.Certificate.property.preCheckDelay"></a>

```go
func PreCheckDelay() *f64
```

- *Type:* *f64

---

##### `PreferredChain`<sup>Required</sup> <a name="PreferredChain" id="@cdktf/provider-acme.certificate.Certificate.property.preferredChain"></a>

```go
func PreferredChain() *string
```

- *Type:* *string

---

##### `Profile`<sup>Required</sup> <a name="Profile" id="@cdktf/provider-acme.certificate.Certificate.property.profile"></a>

```go
func Profile() *string
```

- *Type:* *string

---

##### `RecursiveNameservers`<sup>Required</sup> <a name="RecursiveNameservers" id="@cdktf/provider-acme.certificate.Certificate.property.recursiveNameservers"></a>

```go
func RecursiveNameservers() *[]*string
```

- *Type:* *[]*string

---

##### `RenewalInfoIgnoreRetryAfter`<sup>Required</sup> <a name="RenewalInfoIgnoreRetryAfter" id="@cdktf/provider-acme.certificate.Certificate.property.renewalInfoIgnoreRetryAfter"></a>

```go
func RenewalInfoIgnoreRetryAfter() interface{}
```

- *Type:* interface{}

---

##### `RenewalInfoMaxSleep`<sup>Required</sup> <a name="RenewalInfoMaxSleep" id="@cdktf/provider-acme.certificate.Certificate.property.renewalInfoMaxSleep"></a>

```go
func RenewalInfoMaxSleep() *f64
```

- *Type:* *f64

---

##### `RevokeCertificateOnDestroy`<sup>Required</sup> <a name="RevokeCertificateOnDestroy" id="@cdktf/provider-acme.certificate.Certificate.property.revokeCertificateOnDestroy"></a>

```go
func RevokeCertificateOnDestroy() interface{}
```

- *Type:* interface{}

---

##### `RevokeCertificateReason`<sup>Required</sup> <a name="RevokeCertificateReason" id="@cdktf/provider-acme.certificate.Certificate.property.revokeCertificateReason"></a>

```go
func RevokeCertificateReason() *string
```

- *Type:* *string

---

##### `SubjectAlternativeNames`<sup>Required</sup> <a name="SubjectAlternativeNames" id="@cdktf/provider-acme.certificate.Certificate.property.subjectAlternativeNames"></a>

```go
func SubjectAlternativeNames() *[]*string
```

- *Type:* *[]*string

---

##### `UseRenewalInfo`<sup>Required</sup> <a name="UseRenewalInfo" id="@cdktf/provider-acme.certificate.Certificate.property.useRenewalInfo"></a>

```go
func UseRenewalInfo() interface{}
```

- *Type:* interface{}

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.Certificate.property.tfResourceType">TfResourceType</a></code> | <code>*string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="@cdktf/provider-acme.certificate.Certificate.property.tfResourceType"></a>

```go
func TfResourceType() *string
```

- *Type:* *string

---

## Structs <a name="Structs" id="Structs"></a>

### CertificateConfig <a name="CertificateConfig" id="@cdktf/provider-acme.certificate.CertificateConfig"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-acme.certificate.CertificateConfig.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-acme-go/acme/v12/certificate"

&certificate.CertificateConfig {
	Connection: interface{},
	Count: interface{},
	DependsOn: *[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable,
	ForEach: github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator,
	Lifecycle: github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle,
	Provider: github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider,
	Provisioners: *[]interface{},
	AccountKeyPem: *string,
	CertificateP12Password: *string,
	CertificateRequestPem: *string,
	CertTimeout: *f64,
	CommonName: *string,
	DisableCompletePropagation: interface{},
	DnsChallenge: interface{},
	HttpChallenge: github.com/cdktf/cdktf-provider-acme-go/acme/v12.certificate.CertificateHttpChallenge,
	HttpMemcachedChallenge: github.com/cdktf/cdktf-provider-acme-go/acme/v12.certificate.CertificateHttpMemcachedChallenge,
	HttpS3Challenge: github.com/cdktf/cdktf-provider-acme-go/acme/v12.certificate.CertificateHttpS3Challenge,
	HttpWebrootChallenge: github.com/cdktf/cdktf-provider-acme-go/acme/v12.certificate.CertificateHttpWebrootChallenge,
	Id: *string,
	KeyType: *string,
	MinDaysRemaining: *f64,
	MustStaple: interface{},
	PreCheckDelay: *f64,
	PreferredChain: *string,
	Profile: *string,
	RecursiveNameservers: *[]*string,
	RenewalInfoIgnoreRetryAfter: interface{},
	RenewalInfoMaxSleep: *f64,
	RevokeCertificateOnDestroy: interface{},
	RevokeCertificateReason: *string,
	SubjectAlternativeNames: *[]*string,
	TlsChallenge: github.com/cdktf/cdktf-provider-acme-go/acme/v12.certificate.CertificateTlsChallenge,
	UseRenewalInfo: interface{},
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.connection">Connection</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.count">Count</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.dependsOn">DependsOn</a></code> | <code>*[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.forEach">ForEach</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.lifecycle">Lifecycle</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.provider">Provider</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.provisioners">Provisioners</a></code> | <code>*[]interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.accountKeyPem">AccountKeyPem</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#account_key_pem Certificate#account_key_pem}. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.certificateP12Password">CertificateP12Password</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#certificate_p12_password Certificate#certificate_p12_password}. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.certificateRequestPem">CertificateRequestPem</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#certificate_request_pem Certificate#certificate_request_pem}. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.certTimeout">CertTimeout</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#cert_timeout Certificate#cert_timeout}. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.commonName">CommonName</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#common_name Certificate#common_name}. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.disableCompletePropagation">DisableCompletePropagation</a></code> | <code>interface{}</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#disable_complete_propagation Certificate#disable_complete_propagation}. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.dnsChallenge">DnsChallenge</a></code> | <code>interface{}</code> | dns_challenge block. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.httpChallenge">HttpChallenge</a></code> | <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpChallenge">CertificateHttpChallenge</a></code> | http_challenge block. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.httpMemcachedChallenge">HttpMemcachedChallenge</a></code> | <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallenge">CertificateHttpMemcachedChallenge</a></code> | http_memcached_challenge block. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.httpS3Challenge">HttpS3Challenge</a></code> | <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpS3Challenge">CertificateHttpS3Challenge</a></code> | http_s3_challenge block. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.httpWebrootChallenge">HttpWebrootChallenge</a></code> | <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpWebrootChallenge">CertificateHttpWebrootChallenge</a></code> | http_webroot_challenge block. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.id">Id</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#id Certificate#id}. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.keyType">KeyType</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#key_type Certificate#key_type}. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.minDaysRemaining">MinDaysRemaining</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#min_days_remaining Certificate#min_days_remaining}. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.mustStaple">MustStaple</a></code> | <code>interface{}</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#must_staple Certificate#must_staple}. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.preCheckDelay">PreCheckDelay</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#pre_check_delay Certificate#pre_check_delay}. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.preferredChain">PreferredChain</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#preferred_chain Certificate#preferred_chain}. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.profile">Profile</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#profile Certificate#profile}. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.recursiveNameservers">RecursiveNameservers</a></code> | <code>*[]*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#recursive_nameservers Certificate#recursive_nameservers}. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.renewalInfoIgnoreRetryAfter">RenewalInfoIgnoreRetryAfter</a></code> | <code>interface{}</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#renewal_info_ignore_retry_after Certificate#renewal_info_ignore_retry_after}. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.renewalInfoMaxSleep">RenewalInfoMaxSleep</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#renewal_info_max_sleep Certificate#renewal_info_max_sleep}. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.revokeCertificateOnDestroy">RevokeCertificateOnDestroy</a></code> | <code>interface{}</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#revoke_certificate_on_destroy Certificate#revoke_certificate_on_destroy}. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.revokeCertificateReason">RevokeCertificateReason</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#revoke_certificate_reason Certificate#revoke_certificate_reason}. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.subjectAlternativeNames">SubjectAlternativeNames</a></code> | <code>*[]*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#subject_alternative_names Certificate#subject_alternative_names}. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.tlsChallenge">TlsChallenge</a></code> | <code><a href="#@cdktf/provider-acme.certificate.CertificateTlsChallenge">CertificateTlsChallenge</a></code> | tls_challenge block. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateConfig.property.useRenewalInfo">UseRenewalInfo</a></code> | <code>interface{}</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#use_renewal_info Certificate#use_renewal_info}. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktf/provider-acme.certificate.CertificateConfig.property.connection"></a>

```go
Connection interface{}
```

- *Type:* interface{}

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktf/provider-acme.certificate.CertificateConfig.property.count"></a>

```go
Count interface{}
```

- *Type:* interface{}

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktf/provider-acme.certificate.CertificateConfig.property.dependsOn"></a>

```go
DependsOn *[]ITerraformDependable
```

- *Type:* *[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktf/provider-acme.certificate.CertificateConfig.property.forEach"></a>

```go
ForEach ITerraformIterator
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktf/provider-acme.certificate.CertificateConfig.property.lifecycle"></a>

```go
Lifecycle TerraformResourceLifecycle
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktf/provider-acme.certificate.CertificateConfig.property.provider"></a>

```go
Provider TerraformProvider
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktf/provider-acme.certificate.CertificateConfig.property.provisioners"></a>

```go
Provisioners *[]interface{}
```

- *Type:* *[]interface{}

---

##### `AccountKeyPem`<sup>Required</sup> <a name="AccountKeyPem" id="@cdktf/provider-acme.certificate.CertificateConfig.property.accountKeyPem"></a>

```go
AccountKeyPem *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#account_key_pem Certificate#account_key_pem}.

---

##### `CertificateP12Password`<sup>Optional</sup> <a name="CertificateP12Password" id="@cdktf/provider-acme.certificate.CertificateConfig.property.certificateP12Password"></a>

```go
CertificateP12Password *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#certificate_p12_password Certificate#certificate_p12_password}.

---

##### `CertificateRequestPem`<sup>Optional</sup> <a name="CertificateRequestPem" id="@cdktf/provider-acme.certificate.CertificateConfig.property.certificateRequestPem"></a>

```go
CertificateRequestPem *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#certificate_request_pem Certificate#certificate_request_pem}.

---

##### `CertTimeout`<sup>Optional</sup> <a name="CertTimeout" id="@cdktf/provider-acme.certificate.CertificateConfig.property.certTimeout"></a>

```go
CertTimeout *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#cert_timeout Certificate#cert_timeout}.

---

##### `CommonName`<sup>Optional</sup> <a name="CommonName" id="@cdktf/provider-acme.certificate.CertificateConfig.property.commonName"></a>

```go
CommonName *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#common_name Certificate#common_name}.

---

##### `DisableCompletePropagation`<sup>Optional</sup> <a name="DisableCompletePropagation" id="@cdktf/provider-acme.certificate.CertificateConfig.property.disableCompletePropagation"></a>

```go
DisableCompletePropagation interface{}
```

- *Type:* interface{}

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#disable_complete_propagation Certificate#disable_complete_propagation}.

---

##### `DnsChallenge`<sup>Optional</sup> <a name="DnsChallenge" id="@cdktf/provider-acme.certificate.CertificateConfig.property.dnsChallenge"></a>

```go
DnsChallenge interface{}
```

- *Type:* interface{}

dns_challenge block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#dns_challenge Certificate#dns_challenge}

---

##### `HttpChallenge`<sup>Optional</sup> <a name="HttpChallenge" id="@cdktf/provider-acme.certificate.CertificateConfig.property.httpChallenge"></a>

```go
HttpChallenge CertificateHttpChallenge
```

- *Type:* <a href="#@cdktf/provider-acme.certificate.CertificateHttpChallenge">CertificateHttpChallenge</a>

http_challenge block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#http_challenge Certificate#http_challenge}

---

##### `HttpMemcachedChallenge`<sup>Optional</sup> <a name="HttpMemcachedChallenge" id="@cdktf/provider-acme.certificate.CertificateConfig.property.httpMemcachedChallenge"></a>

```go
HttpMemcachedChallenge CertificateHttpMemcachedChallenge
```

- *Type:* <a href="#@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallenge">CertificateHttpMemcachedChallenge</a>

http_memcached_challenge block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#http_memcached_challenge Certificate#http_memcached_challenge}

---

##### `HttpS3Challenge`<sup>Optional</sup> <a name="HttpS3Challenge" id="@cdktf/provider-acme.certificate.CertificateConfig.property.httpS3Challenge"></a>

```go
HttpS3Challenge CertificateHttpS3Challenge
```

- *Type:* <a href="#@cdktf/provider-acme.certificate.CertificateHttpS3Challenge">CertificateHttpS3Challenge</a>

http_s3_challenge block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#http_s3_challenge Certificate#http_s3_challenge}

---

##### `HttpWebrootChallenge`<sup>Optional</sup> <a name="HttpWebrootChallenge" id="@cdktf/provider-acme.certificate.CertificateConfig.property.httpWebrootChallenge"></a>

```go
HttpWebrootChallenge CertificateHttpWebrootChallenge
```

- *Type:* <a href="#@cdktf/provider-acme.certificate.CertificateHttpWebrootChallenge">CertificateHttpWebrootChallenge</a>

http_webroot_challenge block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#http_webroot_challenge Certificate#http_webroot_challenge}

---

##### `Id`<sup>Optional</sup> <a name="Id" id="@cdktf/provider-acme.certificate.CertificateConfig.property.id"></a>

```go
Id *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#id Certificate#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `KeyType`<sup>Optional</sup> <a name="KeyType" id="@cdktf/provider-acme.certificate.CertificateConfig.property.keyType"></a>

```go
KeyType *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#key_type Certificate#key_type}.

---

##### `MinDaysRemaining`<sup>Optional</sup> <a name="MinDaysRemaining" id="@cdktf/provider-acme.certificate.CertificateConfig.property.minDaysRemaining"></a>

```go
MinDaysRemaining *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#min_days_remaining Certificate#min_days_remaining}.

---

##### `MustStaple`<sup>Optional</sup> <a name="MustStaple" id="@cdktf/provider-acme.certificate.CertificateConfig.property.mustStaple"></a>

```go
MustStaple interface{}
```

- *Type:* interface{}

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#must_staple Certificate#must_staple}.

---

##### `PreCheckDelay`<sup>Optional</sup> <a name="PreCheckDelay" id="@cdktf/provider-acme.certificate.CertificateConfig.property.preCheckDelay"></a>

```go
PreCheckDelay *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#pre_check_delay Certificate#pre_check_delay}.

---

##### `PreferredChain`<sup>Optional</sup> <a name="PreferredChain" id="@cdktf/provider-acme.certificate.CertificateConfig.property.preferredChain"></a>

```go
PreferredChain *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#preferred_chain Certificate#preferred_chain}.

---

##### `Profile`<sup>Optional</sup> <a name="Profile" id="@cdktf/provider-acme.certificate.CertificateConfig.property.profile"></a>

```go
Profile *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#profile Certificate#profile}.

---

##### `RecursiveNameservers`<sup>Optional</sup> <a name="RecursiveNameservers" id="@cdktf/provider-acme.certificate.CertificateConfig.property.recursiveNameservers"></a>

```go
RecursiveNameservers *[]*string
```

- *Type:* *[]*string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#recursive_nameservers Certificate#recursive_nameservers}.

---

##### `RenewalInfoIgnoreRetryAfter`<sup>Optional</sup> <a name="RenewalInfoIgnoreRetryAfter" id="@cdktf/provider-acme.certificate.CertificateConfig.property.renewalInfoIgnoreRetryAfter"></a>

```go
RenewalInfoIgnoreRetryAfter interface{}
```

- *Type:* interface{}

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#renewal_info_ignore_retry_after Certificate#renewal_info_ignore_retry_after}.

---

##### `RenewalInfoMaxSleep`<sup>Optional</sup> <a name="RenewalInfoMaxSleep" id="@cdktf/provider-acme.certificate.CertificateConfig.property.renewalInfoMaxSleep"></a>

```go
RenewalInfoMaxSleep *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#renewal_info_max_sleep Certificate#renewal_info_max_sleep}.

---

##### `RevokeCertificateOnDestroy`<sup>Optional</sup> <a name="RevokeCertificateOnDestroy" id="@cdktf/provider-acme.certificate.CertificateConfig.property.revokeCertificateOnDestroy"></a>

```go
RevokeCertificateOnDestroy interface{}
```

- *Type:* interface{}

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#revoke_certificate_on_destroy Certificate#revoke_certificate_on_destroy}.

---

##### `RevokeCertificateReason`<sup>Optional</sup> <a name="RevokeCertificateReason" id="@cdktf/provider-acme.certificate.CertificateConfig.property.revokeCertificateReason"></a>

```go
RevokeCertificateReason *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#revoke_certificate_reason Certificate#revoke_certificate_reason}.

---

##### `SubjectAlternativeNames`<sup>Optional</sup> <a name="SubjectAlternativeNames" id="@cdktf/provider-acme.certificate.CertificateConfig.property.subjectAlternativeNames"></a>

```go
SubjectAlternativeNames *[]*string
```

- *Type:* *[]*string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#subject_alternative_names Certificate#subject_alternative_names}.

---

##### `TlsChallenge`<sup>Optional</sup> <a name="TlsChallenge" id="@cdktf/provider-acme.certificate.CertificateConfig.property.tlsChallenge"></a>

```go
TlsChallenge CertificateTlsChallenge
```

- *Type:* <a href="#@cdktf/provider-acme.certificate.CertificateTlsChallenge">CertificateTlsChallenge</a>

tls_challenge block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#tls_challenge Certificate#tls_challenge}

---

##### `UseRenewalInfo`<sup>Optional</sup> <a name="UseRenewalInfo" id="@cdktf/provider-acme.certificate.CertificateConfig.property.useRenewalInfo"></a>

```go
UseRenewalInfo interface{}
```

- *Type:* interface{}

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#use_renewal_info Certificate#use_renewal_info}.

---

### CertificateDnsChallenge <a name="CertificateDnsChallenge" id="@cdktf/provider-acme.certificate.CertificateDnsChallenge"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-acme.certificate.CertificateDnsChallenge.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-acme-go/acme/v12/certificate"

&certificate.CertificateDnsChallenge {
	Provider: *string,
	Config: *map[string]*string,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallenge.property.provider">Provider</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#provider Certificate#provider}. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallenge.property.config">Config</a></code> | <code>*map[string]*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#config Certificate#config}. |

---

##### `Provider`<sup>Required</sup> <a name="Provider" id="@cdktf/provider-acme.certificate.CertificateDnsChallenge.property.provider"></a>

```go
Provider *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#provider Certificate#provider}.

---

##### `Config`<sup>Optional</sup> <a name="Config" id="@cdktf/provider-acme.certificate.CertificateDnsChallenge.property.config"></a>

```go
Config *map[string]*string
```

- *Type:* *map[string]*string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#config Certificate#config}.

---

### CertificateHttpChallenge <a name="CertificateHttpChallenge" id="@cdktf/provider-acme.certificate.CertificateHttpChallenge"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-acme.certificate.CertificateHttpChallenge.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-acme-go/acme/v12/certificate"

&certificate.CertificateHttpChallenge {
	Port: *f64,
	ProxyHeader: *string,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpChallenge.property.port">Port</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#port Certificate#port}. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpChallenge.property.proxyHeader">ProxyHeader</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#proxy_header Certificate#proxy_header}. |

---

##### `Port`<sup>Optional</sup> <a name="Port" id="@cdktf/provider-acme.certificate.CertificateHttpChallenge.property.port"></a>

```go
Port *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#port Certificate#port}.

---

##### `ProxyHeader`<sup>Optional</sup> <a name="ProxyHeader" id="@cdktf/provider-acme.certificate.CertificateHttpChallenge.property.proxyHeader"></a>

```go
ProxyHeader *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#proxy_header Certificate#proxy_header}.

---

### CertificateHttpMemcachedChallenge <a name="CertificateHttpMemcachedChallenge" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallenge"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallenge.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-acme-go/acme/v12/certificate"

&certificate.CertificateHttpMemcachedChallenge {
	Hosts: *[]*string,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallenge.property.hosts">Hosts</a></code> | <code>*[]*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#hosts Certificate#hosts}. |

---

##### `Hosts`<sup>Required</sup> <a name="Hosts" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallenge.property.hosts"></a>

```go
Hosts *[]*string
```

- *Type:* *[]*string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#hosts Certificate#hosts}.

---

### CertificateHttpS3Challenge <a name="CertificateHttpS3Challenge" id="@cdktf/provider-acme.certificate.CertificateHttpS3Challenge"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-acme.certificate.CertificateHttpS3Challenge.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-acme-go/acme/v12/certificate"

&certificate.CertificateHttpS3Challenge {
	S3Bucket: *string,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpS3Challenge.property.s3Bucket">S3Bucket</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#s3_bucket Certificate#s3_bucket}. |

---

##### `S3Bucket`<sup>Required</sup> <a name="S3Bucket" id="@cdktf/provider-acme.certificate.CertificateHttpS3Challenge.property.s3Bucket"></a>

```go
S3Bucket *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#s3_bucket Certificate#s3_bucket}.

---

### CertificateHttpWebrootChallenge <a name="CertificateHttpWebrootChallenge" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallenge"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallenge.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-acme-go/acme/v12/certificate"

&certificate.CertificateHttpWebrootChallenge {
	Directory: *string,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpWebrootChallenge.property.directory">Directory</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#directory Certificate#directory}. |

---

##### `Directory`<sup>Required</sup> <a name="Directory" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallenge.property.directory"></a>

```go
Directory *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#directory Certificate#directory}.

---

### CertificateTlsChallenge <a name="CertificateTlsChallenge" id="@cdktf/provider-acme.certificate.CertificateTlsChallenge"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-acme.certificate.CertificateTlsChallenge.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-acme-go/acme/v12/certificate"

&certificate.CertificateTlsChallenge {
	Port: *f64,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateTlsChallenge.property.port">Port</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#port Certificate#port}. |

---

##### `Port`<sup>Optional</sup> <a name="Port" id="@cdktf/provider-acme.certificate.CertificateTlsChallenge.property.port"></a>

```go
Port *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/vancluever/acme/2.39.0/docs/resources/certificate#port Certificate#port}.

---

## Classes <a name="Classes" id="Classes"></a>

### CertificateDnsChallengeList <a name="CertificateDnsChallengeList" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeList"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeList.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-acme-go/acme/v12/certificate"

certificate.NewCertificateDnsChallengeList(terraformResource IInterpolatingParent, terraformAttribute *string, wrapsSet *bool) CertificateDnsChallengeList
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeList.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeList.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeList.Initializer.parameter.wrapsSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeList.allWithMapKey">AllWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeList.get">Get</a></code> | *No description.* |

---

##### `AllWithMapKey` <a name="AllWithMapKey" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeList.allWithMapKey"></a>

```go
func AllWithMapKey(mapKeyAttributeName *string) DynamicListTerraformIterator
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `mapKeyAttributeName`<sup>Required</sup> <a name="mapKeyAttributeName" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* *string

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeList.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `Resolve` <a name="Resolve" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeList.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeList.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeList.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeList.get"></a>

```go
func Get(index *f64) CertificateDnsChallengeOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeList.get.parameter.index"></a>

- *Type:* *f64

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeList.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeList.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeList.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeList.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeList.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeList.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### CertificateDnsChallengeOutputReference <a name="CertificateDnsChallengeOutputReference" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-acme-go/acme/v12/certificate"

certificate.NewCertificateDnsChallengeOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string, complexObjectIndex *f64, complexObjectIsFromSet *bool) CertificateDnsChallengeOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>*f64</code> | the index of this item in the list. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* *f64

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.resetConfig">ResetConfig</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetConfig` <a name="ResetConfig" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.resetConfig"></a>

```go
func ResetConfig()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.property.configInput">ConfigInput</a></code> | <code>*map[string]*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.property.providerInput">ProviderInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.property.config">Config</a></code> | <code>*map[string]*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.property.provider">Provider</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `ConfigInput`<sup>Optional</sup> <a name="ConfigInput" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.property.configInput"></a>

```go
func ConfigInput() *map[string]*string
```

- *Type:* *map[string]*string

---

##### `ProviderInput`<sup>Optional</sup> <a name="ProviderInput" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.property.providerInput"></a>

```go
func ProviderInput() *string
```

- *Type:* *string

---

##### `Config`<sup>Required</sup> <a name="Config" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.property.config"></a>

```go
func Config() *map[string]*string
```

- *Type:* *map[string]*string

---

##### `Provider`<sup>Required</sup> <a name="Provider" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.property.provider"></a>

```go
func Provider() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktf/provider-acme.certificate.CertificateDnsChallengeOutputReference.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### CertificateHttpChallengeOutputReference <a name="CertificateHttpChallengeOutputReference" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-acme-go/acme/v12/certificate"

certificate.NewCertificateHttpChallengeOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string) CertificateHttpChallengeOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.resetPort">ResetPort</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.resetProxyHeader">ResetProxyHeader</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetPort` <a name="ResetPort" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.resetPort"></a>

```go
func ResetPort()
```

##### `ResetProxyHeader` <a name="ResetProxyHeader" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.resetProxyHeader"></a>

```go
func ResetProxyHeader()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.property.portInput">PortInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.property.proxyHeaderInput">ProxyHeaderInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.property.port">Port</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.property.proxyHeader">ProxyHeader</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.property.internalValue">InternalValue</a></code> | <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpChallenge">CertificateHttpChallenge</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `PortInput`<sup>Optional</sup> <a name="PortInput" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.property.portInput"></a>

```go
func PortInput() *f64
```

- *Type:* *f64

---

##### `ProxyHeaderInput`<sup>Optional</sup> <a name="ProxyHeaderInput" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.property.proxyHeaderInput"></a>

```go
func ProxyHeaderInput() *string
```

- *Type:* *string

---

##### `Port`<sup>Required</sup> <a name="Port" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.property.port"></a>

```go
func Port() *f64
```

- *Type:* *f64

---

##### `ProxyHeader`<sup>Required</sup> <a name="ProxyHeader" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.property.proxyHeader"></a>

```go
func ProxyHeader() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktf/provider-acme.certificate.CertificateHttpChallengeOutputReference.property.internalValue"></a>

```go
func InternalValue() CertificateHttpChallenge
```

- *Type:* <a href="#@cdktf/provider-acme.certificate.CertificateHttpChallenge">CertificateHttpChallenge</a>

---


### CertificateHttpMemcachedChallengeOutputReference <a name="CertificateHttpMemcachedChallengeOutputReference" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-acme-go/acme/v12/certificate"

certificate.NewCertificateHttpMemcachedChallengeOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string) CertificateHttpMemcachedChallengeOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.property.hostsInput">HostsInput</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.property.hosts">Hosts</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.property.internalValue">InternalValue</a></code> | <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallenge">CertificateHttpMemcachedChallenge</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `HostsInput`<sup>Optional</sup> <a name="HostsInput" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.property.hostsInput"></a>

```go
func HostsInput() *[]*string
```

- *Type:* *[]*string

---

##### `Hosts`<sup>Required</sup> <a name="Hosts" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.property.hosts"></a>

```go
func Hosts() *[]*string
```

- *Type:* *[]*string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallengeOutputReference.property.internalValue"></a>

```go
func InternalValue() CertificateHttpMemcachedChallenge
```

- *Type:* <a href="#@cdktf/provider-acme.certificate.CertificateHttpMemcachedChallenge">CertificateHttpMemcachedChallenge</a>

---


### CertificateHttpS3ChallengeOutputReference <a name="CertificateHttpS3ChallengeOutputReference" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-acme-go/acme/v12/certificate"

certificate.NewCertificateHttpS3ChallengeOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string) CertificateHttpS3ChallengeOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.property.s3BucketInput">S3BucketInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.property.s3Bucket">S3Bucket</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.property.internalValue">InternalValue</a></code> | <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpS3Challenge">CertificateHttpS3Challenge</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `S3BucketInput`<sup>Optional</sup> <a name="S3BucketInput" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.property.s3BucketInput"></a>

```go
func S3BucketInput() *string
```

- *Type:* *string

---

##### `S3Bucket`<sup>Required</sup> <a name="S3Bucket" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.property.s3Bucket"></a>

```go
func S3Bucket() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktf/provider-acme.certificate.CertificateHttpS3ChallengeOutputReference.property.internalValue"></a>

```go
func InternalValue() CertificateHttpS3Challenge
```

- *Type:* <a href="#@cdktf/provider-acme.certificate.CertificateHttpS3Challenge">CertificateHttpS3Challenge</a>

---


### CertificateHttpWebrootChallengeOutputReference <a name="CertificateHttpWebrootChallengeOutputReference" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-acme-go/acme/v12/certificate"

certificate.NewCertificateHttpWebrootChallengeOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string) CertificateHttpWebrootChallengeOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.property.directoryInput">DirectoryInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.property.directory">Directory</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.property.internalValue">InternalValue</a></code> | <code><a href="#@cdktf/provider-acme.certificate.CertificateHttpWebrootChallenge">CertificateHttpWebrootChallenge</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `DirectoryInput`<sup>Optional</sup> <a name="DirectoryInput" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.property.directoryInput"></a>

```go
func DirectoryInput() *string
```

- *Type:* *string

---

##### `Directory`<sup>Required</sup> <a name="Directory" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.property.directory"></a>

```go
func Directory() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktf/provider-acme.certificate.CertificateHttpWebrootChallengeOutputReference.property.internalValue"></a>

```go
func InternalValue() CertificateHttpWebrootChallenge
```

- *Type:* <a href="#@cdktf/provider-acme.certificate.CertificateHttpWebrootChallenge">CertificateHttpWebrootChallenge</a>

---


### CertificateTlsChallengeOutputReference <a name="CertificateTlsChallengeOutputReference" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-acme-go/acme/v12/certificate"

certificate.NewCertificateTlsChallengeOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string) CertificateTlsChallengeOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.resetPort">ResetPort</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetPort` <a name="ResetPort" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.resetPort"></a>

```go
func ResetPort()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.property.portInput">PortInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.property.port">Port</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.property.internalValue">InternalValue</a></code> | <code><a href="#@cdktf/provider-acme.certificate.CertificateTlsChallenge">CertificateTlsChallenge</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `PortInput`<sup>Optional</sup> <a name="PortInput" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.property.portInput"></a>

```go
func PortInput() *f64
```

- *Type:* *f64

---

##### `Port`<sup>Required</sup> <a name="Port" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.property.port"></a>

```go
func Port() *f64
```

- *Type:* *f64

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktf/provider-acme.certificate.CertificateTlsChallengeOutputReference.property.internalValue"></a>

```go
func InternalValue() CertificateTlsChallenge
```

- *Type:* <a href="#@cdktf/provider-acme.certificate.CertificateTlsChallenge">CertificateTlsChallenge</a>

---



