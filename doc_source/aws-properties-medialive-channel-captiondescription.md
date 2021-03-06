# AWS::MediaLive::Channel CaptionDescription<a name="aws-properties-medialive-channel-captiondescription"></a>

Caption Description

## Syntax<a name="aws-properties-medialive-channel-captiondescription-syntax"></a>

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON<a name="aws-properties-medialive-channel-captiondescription-syntax.json"></a>

```
{
  "[CaptionSelectorName](#cfn-medialive-channel-captiondescription-captionselectorname)" : String,
  "[DestinationSettings](#cfn-medialive-channel-captiondescription-destinationsettings)" : CaptionDestinationSettings,
  "[LanguageCode](#cfn-medialive-channel-captiondescription-languagecode)" : String,
  "[LanguageDescription](#cfn-medialive-channel-captiondescription-languagedescription)" : String,
  "[Name](#cfn-medialive-channel-captiondescription-name)" : String
}
```

### YAML<a name="aws-properties-medialive-channel-captiondescription-syntax.yaml"></a>

```
  [CaptionSelectorName](#cfn-medialive-channel-captiondescription-captionselectorname): String
  [DestinationSettings](#cfn-medialive-channel-captiondescription-destinationsettings): 
    CaptionDestinationSettings
  [LanguageCode](#cfn-medialive-channel-captiondescription-languagecode): String
  [LanguageDescription](#cfn-medialive-channel-captiondescription-languagedescription): String
  [Name](#cfn-medialive-channel-captiondescription-name): String
```

## Properties<a name="aws-properties-medialive-channel-captiondescription-properties"></a>

`CaptionSelectorName`  <a name="cfn-medialive-channel-captiondescription-captionselectorname"></a>
Specifies which input caption selector to use as a caption source when generating output captions\. This field should match a captionSelector name\.  
*Required*: No  
*Type*: String  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

`DestinationSettings`  <a name="cfn-medialive-channel-captiondescription-destinationsettings"></a>
Additional settings for captions destination that depend on the destination type\.  
*Required*: No  
*Type*: [CaptionDestinationSettings](aws-properties-medialive-channel-captiondestinationsettings.md)  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

`LanguageCode`  <a name="cfn-medialive-channel-captiondescription-languagecode"></a>
ISO 639\-2 three\-digit code: http://www\.loc\.gov/standards/iso639\-2/  
*Required*: No  
*Type*: String  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

`LanguageDescription`  <a name="cfn-medialive-channel-captiondescription-languagedescription"></a>
Human readable information to indicate captions available for players \(eg\. English, or Spanish\)\.  
*Required*: No  
*Type*: String  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

`Name`  <a name="cfn-medialive-channel-captiondescription-name"></a>
Name of the caption description\. Used to associate a caption description with an output\. Names must be unique within an event\.  
*Required*: No  
*Type*: String  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)