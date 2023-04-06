### Get value from a tag
Get the value from the tag named "systemid"  

    $tags = Get-AzTag -ResourceId "/subscriptions/$SubscriptionId"
    $tags.Properties.TagsProperty."systemid"