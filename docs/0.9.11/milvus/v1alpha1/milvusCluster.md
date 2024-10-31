---
permalink: /0.9.11/milvus/v1alpha1/milvusCluster/
---

# milvus.v1alpha1.milvusCluster



## Index

* [`fn new(name)`](#fn-new)
* [`obj metadata`](#obj-metadata)
  * [`fn withAnnotations(annotations)`](#fn-metadatawithannotations)
  * [`fn withAnnotationsMixin(annotations)`](#fn-metadatawithannotationsmixin)
  * [`fn withClusterName(clusterName)`](#fn-metadatawithclustername)
  * [`fn withCreationTimestamp(creationTimestamp)`](#fn-metadatawithcreationtimestamp)
  * [`fn withDeletionGracePeriodSeconds(deletionGracePeriodSeconds)`](#fn-metadatawithdeletiongraceperiodseconds)
  * [`fn withDeletionTimestamp(deletionTimestamp)`](#fn-metadatawithdeletiontimestamp)
  * [`fn withFinalizers(finalizers)`](#fn-metadatawithfinalizers)
  * [`fn withFinalizersMixin(finalizers)`](#fn-metadatawithfinalizersmixin)
  * [`fn withGenerateName(generateName)`](#fn-metadatawithgeneratename)
  * [`fn withGeneration(generation)`](#fn-metadatawithgeneration)
  * [`fn withLabels(labels)`](#fn-metadatawithlabels)
  * [`fn withLabelsMixin(labels)`](#fn-metadatawithlabelsmixin)
  * [`fn withName(name)`](#fn-metadatawithname)
  * [`fn withNamespace(namespace)`](#fn-metadatawithnamespace)
  * [`fn withOwnerReferences(ownerReferences)`](#fn-metadatawithownerreferences)
  * [`fn withOwnerReferencesMixin(ownerReferences)`](#fn-metadatawithownerreferencesmixin)
  * [`fn withResourceVersion(resourceVersion)`](#fn-metadatawithresourceversion)
  * [`fn withSelfLink(selfLink)`](#fn-metadatawithselflink)
  * [`fn withUid(uid)`](#fn-metadatawithuid)
* [`obj spec`](#obj-spec)
  * [`fn withConfig(config)`](#fn-specwithconfig)
  * [`fn withConfigMixin(config)`](#fn-specwithconfigmixin)
  * [`obj spec.components`](#obj-speccomponents)
    * [`fn withCommands(commands)`](#fn-speccomponentswithcommands)
    * [`fn withCommandsMixin(commands)`](#fn-speccomponentswithcommandsmixin)
    * [`fn withDisableMetric(disableMetric)`](#fn-speccomponentswithdisablemetric)
    * [`fn withEnableRollingUpdate(enableRollingUpdate)`](#fn-speccomponentswithenablerollingupdate)
    * [`fn withEnv(env)`](#fn-speccomponentswithenv)
    * [`fn withEnvMixin(env)`](#fn-speccomponentswithenvmixin)
    * [`fn withImage(image)`](#fn-speccomponentswithimage)
    * [`fn withImagePullPolicy(imagePullPolicy)`](#fn-speccomponentswithimagepullpolicy)
    * [`fn withImagePullSecrets(imagePullSecrets)`](#fn-speccomponentswithimagepullsecrets)
    * [`fn withImagePullSecretsMixin(imagePullSecrets)`](#fn-speccomponentswithimagepullsecretsmixin)
    * [`fn withImageUpdateMode(imageUpdateMode)`](#fn-speccomponentswithimageupdatemode)
    * [`fn withMetricInterval(metricInterval)`](#fn-speccomponentswithmetricinterval)
    * [`fn withNodeSelector(nodeSelector)`](#fn-speccomponentswithnodeselector)
    * [`fn withNodeSelectorMixin(nodeSelector)`](#fn-speccomponentswithnodeselectormixin)
    * [`fn withPaused(paused)`](#fn-speccomponentswithpaused)
    * [`fn withPodAnnotations(podAnnotations)`](#fn-speccomponentswithpodannotations)
    * [`fn withPodAnnotationsMixin(podAnnotations)`](#fn-speccomponentswithpodannotationsmixin)
    * [`fn withPodLabels(podLabels)`](#fn-speccomponentswithpodlabels)
    * [`fn withPodLabelsMixin(podLabels)`](#fn-speccomponentswithpodlabelsmixin)
    * [`fn withPriorityClassName(priorityClassName)`](#fn-speccomponentswithpriorityclassname)
    * [`fn withRunWithSubProcess(runWithSubProcess)`](#fn-speccomponentswithrunwithsubprocess)
    * [`fn withSchedulerName(schedulerName)`](#fn-speccomponentswithschedulername)
    * [`fn withServiceAccountName(serviceAccountName)`](#fn-speccomponentswithserviceaccountname)
    * [`fn withTolerations(tolerations)`](#fn-speccomponentswithtolerations)
    * [`fn withTolerationsMixin(tolerations)`](#fn-speccomponentswithtolerationsmixin)
    * [`fn withToolImage(toolImage)`](#fn-speccomponentswithtoolimage)
    * [`fn withUpdateConfigMapOnly(updateConfigMapOnly)`](#fn-speccomponentswithupdateconfigmaponly)
    * [`fn withUpdateToolImage(updateToolImage)`](#fn-speccomponentswithupdatetoolimage)
    * [`fn withVolumeMounts(volumeMounts)`](#fn-speccomponentswithvolumemounts)
    * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-speccomponentswithvolumemountsmixin)
    * [`fn withVolumes(volumes)`](#fn-speccomponentswithvolumes)
    * [`fn withVolumesMixin(volumes)`](#fn-speccomponentswithvolumesmixin)
    * [`obj spec.components.affinity`](#obj-speccomponentsaffinity)
      * [`obj spec.components.affinity.nodeAffinity`](#obj-speccomponentsaffinitynodeaffinity)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecution)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
        * [`obj spec.components.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsaffinitynodeaffinitypreferredduringschedulingignoredduringexecution)
          * [`fn withWeight(weight)`](#fn-speccomponentsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionwithweight)
          * [`obj spec.components.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference`](#obj-speccomponentsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreference)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressionsmixin)
            * [`fn withMatchFields(matchFields)`](#fn-speccomponentsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfields)
            * [`fn withMatchFieldsMixin(matchFields)`](#fn-speccomponentsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfieldsmixin)
            * [`obj spec.components.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions`](#obj-speccomponentsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressions)
              * [`fn withKey(key)`](#fn-speccomponentsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-speccomponentsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-speccomponentsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-speccomponentsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvaluesmixin)
            * [`obj spec.components.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields`](#obj-speccomponentsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfields)
              * [`fn withKey(key)`](#fn-speccomponentsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithkey)
              * [`fn withOperator(operator)`](#fn-speccomponentsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithoperator)
              * [`fn withValues(values)`](#fn-speccomponentsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvalues)
              * [`fn withValuesMixin(values)`](#fn-speccomponentsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvaluesmixin)
        * [`obj spec.components.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsaffinitynodeaffinityrequiredduringschedulingignoredduringexecution)
          * [`fn withNodeSelectorTerms(nodeSelectorTerms)`](#fn-speccomponentsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectorterms)
          * [`fn withNodeSelectorTermsMixin(nodeSelectorTerms)`](#fn-speccomponentsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectortermsmixin)
          * [`obj spec.components.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms`](#obj-speccomponentsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectorterms)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressionsmixin)
            * [`fn withMatchFields(matchFields)`](#fn-speccomponentsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfields)
            * [`fn withMatchFieldsMixin(matchFields)`](#fn-speccomponentsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfieldsmixin)
            * [`obj spec.components.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions`](#obj-speccomponentsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressions)
              * [`fn withKey(key)`](#fn-speccomponentsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-speccomponentsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-speccomponentsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-speccomponentsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvaluesmixin)
            * [`obj spec.components.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields`](#obj-speccomponentsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfields)
              * [`fn withKey(key)`](#fn-speccomponentsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithkey)
              * [`fn withOperator(operator)`](#fn-speccomponentsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithoperator)
              * [`fn withValues(values)`](#fn-speccomponentsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvalues)
              * [`fn withValuesMixin(values)`](#fn-speccomponentsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvaluesmixin)
      * [`obj spec.components.affinity.podAffinity`](#obj-speccomponentsaffinitypodaffinity)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsaffinitypodaffinitywithpreferredduringschedulingignoredduringexecution)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsaffinitypodaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
        * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsaffinitypodaffinitywithrequiredduringschedulingignoredduringexecution)
        * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsaffinitypodaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
        * [`obj spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsaffinitypodaffinitypreferredduringschedulingignoredduringexecution)
          * [`fn withWeight(weight)`](#fn-speccomponentsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionwithweight)
          * [`obj spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-speccomponentsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
            * [`fn withNamespaces(namespaces)`](#fn-speccomponentsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
            * [`obj spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-speccomponentsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
              * [`obj spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-speccomponentsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-speccomponentsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-speccomponentsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
        * [`obj spec.components.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsaffinitypodaffinityrequiredduringschedulingignoredduringexecution)
          * [`fn withNamespaces(namespaces)`](#fn-speccomponentsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
          * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
          * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
          * [`obj spec.components.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-speccomponentsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
            * [`obj spec.components.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-speccomponentsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
              * [`fn withKey(key)`](#fn-speccomponentsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-speccomponentsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-speccomponentsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-speccomponentsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
          * [`obj spec.components.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-speccomponentsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
            * [`obj spec.components.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-speccomponentsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
              * [`fn withKey(key)`](#fn-speccomponentsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-speccomponentsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-speccomponentsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-speccomponentsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
      * [`obj spec.components.affinity.podAntiAffinity`](#obj-speccomponentsaffinitypodantiaffinity)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecution)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
        * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecution)
        * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
        * [`obj spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecution)
          * [`fn withWeight(weight)`](#fn-speccomponentsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionwithweight)
          * [`obj spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-speccomponentsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
            * [`fn withNamespaces(namespaces)`](#fn-speccomponentsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
            * [`obj spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-speccomponentsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
              * [`obj spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-speccomponentsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-speccomponentsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-speccomponentsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
        * [`obj spec.components.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecution)
          * [`fn withNamespaces(namespaces)`](#fn-speccomponentsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
          * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
          * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
          * [`obj spec.components.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-speccomponentsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
            * [`obj spec.components.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-speccomponentsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
              * [`fn withKey(key)`](#fn-speccomponentsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-speccomponentsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-speccomponentsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-speccomponentsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
          * [`obj spec.components.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-speccomponentsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
            * [`obj spec.components.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-speccomponentsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
              * [`fn withKey(key)`](#fn-speccomponentsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-speccomponentsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-speccomponentsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-speccomponentsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
    * [`obj spec.components.dataCoord`](#obj-speccomponentsdatacoord)
      * [`fn withCommands(commands)`](#fn-speccomponentsdatacoordwithcommands)
      * [`fn withCommandsMixin(commands)`](#fn-speccomponentsdatacoordwithcommandsmixin)
      * [`fn withEnv(env)`](#fn-speccomponentsdatacoordwithenv)
      * [`fn withEnvMixin(env)`](#fn-speccomponentsdatacoordwithenvmixin)
      * [`fn withImage(image)`](#fn-speccomponentsdatacoordwithimage)
      * [`fn withImagePullPolicy(imagePullPolicy)`](#fn-speccomponentsdatacoordwithimagepullpolicy)
      * [`fn withImagePullSecrets(imagePullSecrets)`](#fn-speccomponentsdatacoordwithimagepullsecrets)
      * [`fn withImagePullSecretsMixin(imagePullSecrets)`](#fn-speccomponentsdatacoordwithimagepullsecretsmixin)
      * [`fn withInitContainers(initContainers)`](#fn-speccomponentsdatacoordwithinitcontainers)
      * [`fn withInitContainersMixin(initContainers)`](#fn-speccomponentsdatacoordwithinitcontainersmixin)
      * [`fn withNodeSelector(nodeSelector)`](#fn-speccomponentsdatacoordwithnodeselector)
      * [`fn withNodeSelectorMixin(nodeSelector)`](#fn-speccomponentsdatacoordwithnodeselectormixin)
      * [`fn withPaused(paused)`](#fn-speccomponentsdatacoordwithpaused)
      * [`fn withPodAnnotations(podAnnotations)`](#fn-speccomponentsdatacoordwithpodannotations)
      * [`fn withPodAnnotationsMixin(podAnnotations)`](#fn-speccomponentsdatacoordwithpodannotationsmixin)
      * [`fn withPodLabels(podLabels)`](#fn-speccomponentsdatacoordwithpodlabels)
      * [`fn withPodLabelsMixin(podLabels)`](#fn-speccomponentsdatacoordwithpodlabelsmixin)
      * [`fn withPort(port)`](#fn-speccomponentsdatacoordwithport)
      * [`fn withPriorityClassName(priorityClassName)`](#fn-speccomponentsdatacoordwithpriorityclassname)
      * [`fn withReplicas(replicas)`](#fn-speccomponentsdatacoordwithreplicas)
      * [`fn withRunWithSubProcess(runWithSubProcess)`](#fn-speccomponentsdatacoordwithrunwithsubprocess)
      * [`fn withSchedulerName(schedulerName)`](#fn-speccomponentsdatacoordwithschedulername)
      * [`fn withServiceAccountName(serviceAccountName)`](#fn-speccomponentsdatacoordwithserviceaccountname)
      * [`fn withSidecars(sidecars)`](#fn-speccomponentsdatacoordwithsidecars)
      * [`fn withSidecarsMixin(sidecars)`](#fn-speccomponentsdatacoordwithsidecarsmixin)
      * [`fn withTolerations(tolerations)`](#fn-speccomponentsdatacoordwithtolerations)
      * [`fn withTolerationsMixin(tolerations)`](#fn-speccomponentsdatacoordwithtolerationsmixin)
      * [`fn withVolumeMounts(volumeMounts)`](#fn-speccomponentsdatacoordwithvolumemounts)
      * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-speccomponentsdatacoordwithvolumemountsmixin)
      * [`fn withVolumes(volumes)`](#fn-speccomponentsdatacoordwithvolumes)
      * [`fn withVolumesMixin(volumes)`](#fn-speccomponentsdatacoordwithvolumesmixin)
      * [`obj spec.components.dataCoord.affinity`](#obj-speccomponentsdatacoordaffinity)
        * [`obj spec.components.dataCoord.affinity.nodeAffinity`](#obj-speccomponentsdatacoordaffinitynodeaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsdatacoordaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsdatacoordaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.components.dataCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsdatacoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-speccomponentsdatacoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.components.dataCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference`](#obj-speccomponentsdatacoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreference)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsdatacoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsdatacoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressionsmixin)
              * [`fn withMatchFields(matchFields)`](#fn-speccomponentsdatacoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfields)
              * [`fn withMatchFieldsMixin(matchFields)`](#fn-speccomponentsdatacoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfieldsmixin)
              * [`obj spec.components.dataCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions`](#obj-speccomponentsdatacoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsdatacoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsdatacoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsdatacoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsdatacoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvaluesmixin)
              * [`obj spec.components.dataCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields`](#obj-speccomponentsdatacoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfields)
                * [`fn withKey(key)`](#fn-speccomponentsdatacoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsdatacoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsdatacoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsdatacoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvaluesmixin)
          * [`obj spec.components.dataCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsdatacoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNodeSelectorTerms(nodeSelectorTerms)`](#fn-speccomponentsdatacoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectorterms)
            * [`fn withNodeSelectorTermsMixin(nodeSelectorTerms)`](#fn-speccomponentsdatacoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectortermsmixin)
            * [`obj spec.components.dataCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms`](#obj-speccomponentsdatacoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectorterms)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsdatacoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsdatacoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressionsmixin)
              * [`fn withMatchFields(matchFields)`](#fn-speccomponentsdatacoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfields)
              * [`fn withMatchFieldsMixin(matchFields)`](#fn-speccomponentsdatacoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfieldsmixin)
              * [`obj spec.components.dataCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions`](#obj-speccomponentsdatacoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsdatacoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsdatacoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsdatacoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsdatacoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvaluesmixin)
              * [`obj spec.components.dataCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields`](#obj-speccomponentsdatacoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfields)
                * [`fn withKey(key)`](#fn-speccomponentsdatacoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsdatacoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsdatacoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsdatacoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvaluesmixin)
        * [`obj spec.components.dataCoord.affinity.podAffinity`](#obj-speccomponentsdatacoordaffinitypodaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsdatacoordaffinitypodaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsdatacoordaffinitypodaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsdatacoordaffinitypodaffinitywithrequiredduringschedulingignoredduringexecution)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsdatacoordaffinitypodaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsdatacoordaffinitypodaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-speccomponentsdatacoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-speccomponentsdatacoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
              * [`fn withNamespaces(namespaces)`](#fn-speccomponentsdatacoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
              * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsdatacoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
              * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsdatacoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
              * [`obj spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-speccomponentsdatacoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsdatacoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsdatacoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsdatacoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsdatacoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                * [`obj spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-speccomponentsdatacoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsdatacoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsdatacoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsdatacoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsdatacoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-speccomponentsdatacoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsdatacoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsdatacoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsdatacoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsdatacoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                * [`obj spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-speccomponentsdatacoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsdatacoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsdatacoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsdatacoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsdatacoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
          * [`obj spec.components.dataCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsdatacoordaffinitypodaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNamespaces(namespaces)`](#fn-speccomponentsdatacoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsdatacoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsdatacoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
            * [`obj spec.components.dataCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-speccomponentsdatacoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsdatacoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsdatacoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsdatacoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsdatacoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
              * [`obj spec.components.dataCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-speccomponentsdatacoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsdatacoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsdatacoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsdatacoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsdatacoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.components.dataCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-speccomponentsdatacoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsdatacoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsdatacoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsdatacoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsdatacoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.components.dataCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-speccomponentsdatacoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsdatacoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsdatacoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsdatacoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsdatacoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
        * [`obj spec.components.dataCoord.affinity.podAntiAffinity`](#obj-speccomponentsdatacoordaffinitypodantiaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsdatacoordaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsdatacoordaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsdatacoordaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecution)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsdatacoordaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsdatacoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-speccomponentsdatacoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-speccomponentsdatacoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
              * [`fn withNamespaces(namespaces)`](#fn-speccomponentsdatacoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
              * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsdatacoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
              * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsdatacoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
              * [`obj spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-speccomponentsdatacoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsdatacoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsdatacoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsdatacoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsdatacoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                * [`obj spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-speccomponentsdatacoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsdatacoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsdatacoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsdatacoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsdatacoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-speccomponentsdatacoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsdatacoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsdatacoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsdatacoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsdatacoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                * [`obj spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-speccomponentsdatacoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsdatacoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsdatacoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsdatacoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsdatacoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
          * [`obj spec.components.dataCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsdatacoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNamespaces(namespaces)`](#fn-speccomponentsdatacoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsdatacoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsdatacoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
            * [`obj spec.components.dataCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-speccomponentsdatacoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsdatacoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsdatacoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsdatacoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsdatacoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
              * [`obj spec.components.dataCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-speccomponentsdatacoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsdatacoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsdatacoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsdatacoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsdatacoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.components.dataCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-speccomponentsdatacoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsdatacoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsdatacoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsdatacoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsdatacoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.components.dataCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-speccomponentsdatacoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsdatacoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsdatacoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsdatacoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsdatacoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
      * [`obj spec.components.dataCoord.env`](#obj-speccomponentsdatacoordenv)
        * [`fn withName(name)`](#fn-speccomponentsdatacoordenvwithname)
        * [`fn withValue(value)`](#fn-speccomponentsdatacoordenvwithvalue)
        * [`obj spec.components.dataCoord.env.valueFrom`](#obj-speccomponentsdatacoordenvvaluefrom)
          * [`obj spec.components.dataCoord.env.valueFrom.configMapKeyRef`](#obj-speccomponentsdatacoordenvvaluefromconfigmapkeyref)
            * [`fn withKey(key)`](#fn-speccomponentsdatacoordenvvaluefromconfigmapkeyrefwithkey)
            * [`fn withName(name)`](#fn-speccomponentsdatacoordenvvaluefromconfigmapkeyrefwithname)
            * [`fn withOptional(optional)`](#fn-speccomponentsdatacoordenvvaluefromconfigmapkeyrefwithoptional)
          * [`obj spec.components.dataCoord.env.valueFrom.fieldRef`](#obj-speccomponentsdatacoordenvvaluefromfieldref)
            * [`fn withApiVersion(apiVersion)`](#fn-speccomponentsdatacoordenvvaluefromfieldrefwithapiversion)
            * [`fn withFieldPath(fieldPath)`](#fn-speccomponentsdatacoordenvvaluefromfieldrefwithfieldpath)
          * [`obj spec.components.dataCoord.env.valueFrom.resourceFieldRef`](#obj-speccomponentsdatacoordenvvaluefromresourcefieldref)
            * [`fn withContainerName(containerName)`](#fn-speccomponentsdatacoordenvvaluefromresourcefieldrefwithcontainername)
            * [`fn withDivisor(divisor)`](#fn-speccomponentsdatacoordenvvaluefromresourcefieldrefwithdivisor)
            * [`fn withResource(resource)`](#fn-speccomponentsdatacoordenvvaluefromresourcefieldrefwithresource)
          * [`obj spec.components.dataCoord.env.valueFrom.secretKeyRef`](#obj-speccomponentsdatacoordenvvaluefromsecretkeyref)
            * [`fn withKey(key)`](#fn-speccomponentsdatacoordenvvaluefromsecretkeyrefwithkey)
            * [`fn withName(name)`](#fn-speccomponentsdatacoordenvvaluefromsecretkeyrefwithname)
            * [`fn withOptional(optional)`](#fn-speccomponentsdatacoordenvvaluefromsecretkeyrefwithoptional)
      * [`obj spec.components.dataCoord.imagePullSecrets`](#obj-speccomponentsdatacoordimagepullsecrets)
        * [`fn withName(name)`](#fn-speccomponentsdatacoordimagepullsecretswithname)
      * [`obj spec.components.dataCoord.resources`](#obj-speccomponentsdatacoordresources)
        * [`fn withLimits(limits)`](#fn-speccomponentsdatacoordresourceswithlimits)
        * [`fn withLimitsMixin(limits)`](#fn-speccomponentsdatacoordresourceswithlimitsmixin)
        * [`fn withRequests(requests)`](#fn-speccomponentsdatacoordresourceswithrequests)
        * [`fn withRequestsMixin(requests)`](#fn-speccomponentsdatacoordresourceswithrequestsmixin)
      * [`obj spec.components.dataCoord.tolerations`](#obj-speccomponentsdatacoordtolerations)
        * [`fn withEffect(effect)`](#fn-speccomponentsdatacoordtolerationswitheffect)
        * [`fn withKey(key)`](#fn-speccomponentsdatacoordtolerationswithkey)
        * [`fn withOperator(operator)`](#fn-speccomponentsdatacoordtolerationswithoperator)
        * [`fn withTolerationSeconds(tolerationSeconds)`](#fn-speccomponentsdatacoordtolerationswithtolerationseconds)
        * [`fn withValue(value)`](#fn-speccomponentsdatacoordtolerationswithvalue)
      * [`obj spec.components.dataCoord.volumeMounts`](#obj-speccomponentsdatacoordvolumemounts)
        * [`fn withMountPath(mountPath)`](#fn-speccomponentsdatacoordvolumemountswithmountpath)
        * [`fn withMountPropagation(mountPropagation)`](#fn-speccomponentsdatacoordvolumemountswithmountpropagation)
        * [`fn withName(name)`](#fn-speccomponentsdatacoordvolumemountswithname)
        * [`fn withReadOnly(readOnly)`](#fn-speccomponentsdatacoordvolumemountswithreadonly)
        * [`fn withSubPath(subPath)`](#fn-speccomponentsdatacoordvolumemountswithsubpath)
        * [`fn withSubPathExpr(subPathExpr)`](#fn-speccomponentsdatacoordvolumemountswithsubpathexpr)
    * [`obj spec.components.dataNode`](#obj-speccomponentsdatanode)
      * [`fn withCommands(commands)`](#fn-speccomponentsdatanodewithcommands)
      * [`fn withCommandsMixin(commands)`](#fn-speccomponentsdatanodewithcommandsmixin)
      * [`fn withEnv(env)`](#fn-speccomponentsdatanodewithenv)
      * [`fn withEnvMixin(env)`](#fn-speccomponentsdatanodewithenvmixin)
      * [`fn withImage(image)`](#fn-speccomponentsdatanodewithimage)
      * [`fn withImagePullPolicy(imagePullPolicy)`](#fn-speccomponentsdatanodewithimagepullpolicy)
      * [`fn withImagePullSecrets(imagePullSecrets)`](#fn-speccomponentsdatanodewithimagepullsecrets)
      * [`fn withImagePullSecretsMixin(imagePullSecrets)`](#fn-speccomponentsdatanodewithimagepullsecretsmixin)
      * [`fn withInitContainers(initContainers)`](#fn-speccomponentsdatanodewithinitcontainers)
      * [`fn withInitContainersMixin(initContainers)`](#fn-speccomponentsdatanodewithinitcontainersmixin)
      * [`fn withNodeSelector(nodeSelector)`](#fn-speccomponentsdatanodewithnodeselector)
      * [`fn withNodeSelectorMixin(nodeSelector)`](#fn-speccomponentsdatanodewithnodeselectormixin)
      * [`fn withPaused(paused)`](#fn-speccomponentsdatanodewithpaused)
      * [`fn withPodAnnotations(podAnnotations)`](#fn-speccomponentsdatanodewithpodannotations)
      * [`fn withPodAnnotationsMixin(podAnnotations)`](#fn-speccomponentsdatanodewithpodannotationsmixin)
      * [`fn withPodLabels(podLabels)`](#fn-speccomponentsdatanodewithpodlabels)
      * [`fn withPodLabelsMixin(podLabels)`](#fn-speccomponentsdatanodewithpodlabelsmixin)
      * [`fn withPort(port)`](#fn-speccomponentsdatanodewithport)
      * [`fn withPriorityClassName(priorityClassName)`](#fn-speccomponentsdatanodewithpriorityclassname)
      * [`fn withReplicas(replicas)`](#fn-speccomponentsdatanodewithreplicas)
      * [`fn withRunWithSubProcess(runWithSubProcess)`](#fn-speccomponentsdatanodewithrunwithsubprocess)
      * [`fn withSchedulerName(schedulerName)`](#fn-speccomponentsdatanodewithschedulername)
      * [`fn withServiceAccountName(serviceAccountName)`](#fn-speccomponentsdatanodewithserviceaccountname)
      * [`fn withSidecars(sidecars)`](#fn-speccomponentsdatanodewithsidecars)
      * [`fn withSidecarsMixin(sidecars)`](#fn-speccomponentsdatanodewithsidecarsmixin)
      * [`fn withTolerations(tolerations)`](#fn-speccomponentsdatanodewithtolerations)
      * [`fn withTolerationsMixin(tolerations)`](#fn-speccomponentsdatanodewithtolerationsmixin)
      * [`fn withVolumeMounts(volumeMounts)`](#fn-speccomponentsdatanodewithvolumemounts)
      * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-speccomponentsdatanodewithvolumemountsmixin)
      * [`fn withVolumes(volumes)`](#fn-speccomponentsdatanodewithvolumes)
      * [`fn withVolumesMixin(volumes)`](#fn-speccomponentsdatanodewithvolumesmixin)
      * [`obj spec.components.dataNode.affinity`](#obj-speccomponentsdatanodeaffinity)
        * [`obj spec.components.dataNode.affinity.nodeAffinity`](#obj-speccomponentsdatanodeaffinitynodeaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsdatanodeaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsdatanodeaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.components.dataNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsdatanodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-speccomponentsdatanodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.components.dataNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference`](#obj-speccomponentsdatanodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreference)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsdatanodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsdatanodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressionsmixin)
              * [`fn withMatchFields(matchFields)`](#fn-speccomponentsdatanodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfields)
              * [`fn withMatchFieldsMixin(matchFields)`](#fn-speccomponentsdatanodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfieldsmixin)
              * [`obj spec.components.dataNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions`](#obj-speccomponentsdatanodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsdatanodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsdatanodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsdatanodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsdatanodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvaluesmixin)
              * [`obj spec.components.dataNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields`](#obj-speccomponentsdatanodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfields)
                * [`fn withKey(key)`](#fn-speccomponentsdatanodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsdatanodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsdatanodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsdatanodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvaluesmixin)
          * [`obj spec.components.dataNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsdatanodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNodeSelectorTerms(nodeSelectorTerms)`](#fn-speccomponentsdatanodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectorterms)
            * [`fn withNodeSelectorTermsMixin(nodeSelectorTerms)`](#fn-speccomponentsdatanodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectortermsmixin)
            * [`obj spec.components.dataNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms`](#obj-speccomponentsdatanodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectorterms)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsdatanodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsdatanodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressionsmixin)
              * [`fn withMatchFields(matchFields)`](#fn-speccomponentsdatanodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfields)
              * [`fn withMatchFieldsMixin(matchFields)`](#fn-speccomponentsdatanodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfieldsmixin)
              * [`obj spec.components.dataNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions`](#obj-speccomponentsdatanodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsdatanodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsdatanodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsdatanodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsdatanodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvaluesmixin)
              * [`obj spec.components.dataNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields`](#obj-speccomponentsdatanodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfields)
                * [`fn withKey(key)`](#fn-speccomponentsdatanodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsdatanodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsdatanodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsdatanodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvaluesmixin)
        * [`obj spec.components.dataNode.affinity.podAffinity`](#obj-speccomponentsdatanodeaffinitypodaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsdatanodeaffinitypodaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsdatanodeaffinitypodaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsdatanodeaffinitypodaffinitywithrequiredduringschedulingignoredduringexecution)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsdatanodeaffinitypodaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsdatanodeaffinitypodaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-speccomponentsdatanodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-speccomponentsdatanodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
              * [`fn withNamespaces(namespaces)`](#fn-speccomponentsdatanodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
              * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsdatanodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
              * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsdatanodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
              * [`obj spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-speccomponentsdatanodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsdatanodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsdatanodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsdatanodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsdatanodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                * [`obj spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-speccomponentsdatanodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsdatanodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsdatanodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsdatanodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsdatanodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-speccomponentsdatanodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsdatanodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsdatanodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsdatanodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsdatanodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                * [`obj spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-speccomponentsdatanodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsdatanodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsdatanodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsdatanodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsdatanodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
          * [`obj spec.components.dataNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsdatanodeaffinitypodaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNamespaces(namespaces)`](#fn-speccomponentsdatanodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsdatanodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsdatanodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
            * [`obj spec.components.dataNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-speccomponentsdatanodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsdatanodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsdatanodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsdatanodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsdatanodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
              * [`obj spec.components.dataNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-speccomponentsdatanodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsdatanodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsdatanodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsdatanodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsdatanodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.components.dataNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-speccomponentsdatanodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsdatanodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsdatanodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsdatanodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsdatanodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.components.dataNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-speccomponentsdatanodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsdatanodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsdatanodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsdatanodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsdatanodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
        * [`obj spec.components.dataNode.affinity.podAntiAffinity`](#obj-speccomponentsdatanodeaffinitypodantiaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsdatanodeaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsdatanodeaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsdatanodeaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecution)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsdatanodeaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsdatanodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-speccomponentsdatanodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-speccomponentsdatanodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
              * [`fn withNamespaces(namespaces)`](#fn-speccomponentsdatanodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
              * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsdatanodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
              * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsdatanodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
              * [`obj spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-speccomponentsdatanodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsdatanodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsdatanodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsdatanodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsdatanodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                * [`obj spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-speccomponentsdatanodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsdatanodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsdatanodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsdatanodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsdatanodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-speccomponentsdatanodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsdatanodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsdatanodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsdatanodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsdatanodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                * [`obj spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-speccomponentsdatanodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsdatanodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsdatanodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsdatanodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsdatanodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
          * [`obj spec.components.dataNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsdatanodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNamespaces(namespaces)`](#fn-speccomponentsdatanodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsdatanodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsdatanodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
            * [`obj spec.components.dataNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-speccomponentsdatanodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsdatanodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsdatanodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsdatanodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsdatanodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
              * [`obj spec.components.dataNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-speccomponentsdatanodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsdatanodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsdatanodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsdatanodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsdatanodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.components.dataNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-speccomponentsdatanodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsdatanodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsdatanodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsdatanodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsdatanodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.components.dataNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-speccomponentsdatanodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsdatanodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsdatanodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsdatanodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsdatanodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
      * [`obj spec.components.dataNode.env`](#obj-speccomponentsdatanodeenv)
        * [`fn withName(name)`](#fn-speccomponentsdatanodeenvwithname)
        * [`fn withValue(value)`](#fn-speccomponentsdatanodeenvwithvalue)
        * [`obj spec.components.dataNode.env.valueFrom`](#obj-speccomponentsdatanodeenvvaluefrom)
          * [`obj spec.components.dataNode.env.valueFrom.configMapKeyRef`](#obj-speccomponentsdatanodeenvvaluefromconfigmapkeyref)
            * [`fn withKey(key)`](#fn-speccomponentsdatanodeenvvaluefromconfigmapkeyrefwithkey)
            * [`fn withName(name)`](#fn-speccomponentsdatanodeenvvaluefromconfigmapkeyrefwithname)
            * [`fn withOptional(optional)`](#fn-speccomponentsdatanodeenvvaluefromconfigmapkeyrefwithoptional)
          * [`obj spec.components.dataNode.env.valueFrom.fieldRef`](#obj-speccomponentsdatanodeenvvaluefromfieldref)
            * [`fn withApiVersion(apiVersion)`](#fn-speccomponentsdatanodeenvvaluefromfieldrefwithapiversion)
            * [`fn withFieldPath(fieldPath)`](#fn-speccomponentsdatanodeenvvaluefromfieldrefwithfieldpath)
          * [`obj spec.components.dataNode.env.valueFrom.resourceFieldRef`](#obj-speccomponentsdatanodeenvvaluefromresourcefieldref)
            * [`fn withContainerName(containerName)`](#fn-speccomponentsdatanodeenvvaluefromresourcefieldrefwithcontainername)
            * [`fn withDivisor(divisor)`](#fn-speccomponentsdatanodeenvvaluefromresourcefieldrefwithdivisor)
            * [`fn withResource(resource)`](#fn-speccomponentsdatanodeenvvaluefromresourcefieldrefwithresource)
          * [`obj spec.components.dataNode.env.valueFrom.secretKeyRef`](#obj-speccomponentsdatanodeenvvaluefromsecretkeyref)
            * [`fn withKey(key)`](#fn-speccomponentsdatanodeenvvaluefromsecretkeyrefwithkey)
            * [`fn withName(name)`](#fn-speccomponentsdatanodeenvvaluefromsecretkeyrefwithname)
            * [`fn withOptional(optional)`](#fn-speccomponentsdatanodeenvvaluefromsecretkeyrefwithoptional)
      * [`obj spec.components.dataNode.imagePullSecrets`](#obj-speccomponentsdatanodeimagepullsecrets)
        * [`fn withName(name)`](#fn-speccomponentsdatanodeimagepullsecretswithname)
      * [`obj spec.components.dataNode.resources`](#obj-speccomponentsdatanoderesources)
        * [`fn withLimits(limits)`](#fn-speccomponentsdatanoderesourceswithlimits)
        * [`fn withLimitsMixin(limits)`](#fn-speccomponentsdatanoderesourceswithlimitsmixin)
        * [`fn withRequests(requests)`](#fn-speccomponentsdatanoderesourceswithrequests)
        * [`fn withRequestsMixin(requests)`](#fn-speccomponentsdatanoderesourceswithrequestsmixin)
      * [`obj spec.components.dataNode.tolerations`](#obj-speccomponentsdatanodetolerations)
        * [`fn withEffect(effect)`](#fn-speccomponentsdatanodetolerationswitheffect)
        * [`fn withKey(key)`](#fn-speccomponentsdatanodetolerationswithkey)
        * [`fn withOperator(operator)`](#fn-speccomponentsdatanodetolerationswithoperator)
        * [`fn withTolerationSeconds(tolerationSeconds)`](#fn-speccomponentsdatanodetolerationswithtolerationseconds)
        * [`fn withValue(value)`](#fn-speccomponentsdatanodetolerationswithvalue)
      * [`obj spec.components.dataNode.volumeMounts`](#obj-speccomponentsdatanodevolumemounts)
        * [`fn withMountPath(mountPath)`](#fn-speccomponentsdatanodevolumemountswithmountpath)
        * [`fn withMountPropagation(mountPropagation)`](#fn-speccomponentsdatanodevolumemountswithmountpropagation)
        * [`fn withName(name)`](#fn-speccomponentsdatanodevolumemountswithname)
        * [`fn withReadOnly(readOnly)`](#fn-speccomponentsdatanodevolumemountswithreadonly)
        * [`fn withSubPath(subPath)`](#fn-speccomponentsdatanodevolumemountswithsubpath)
        * [`fn withSubPathExpr(subPathExpr)`](#fn-speccomponentsdatanodevolumemountswithsubpathexpr)
    * [`obj spec.components.env`](#obj-speccomponentsenv)
      * [`fn withName(name)`](#fn-speccomponentsenvwithname)
      * [`fn withValue(value)`](#fn-speccomponentsenvwithvalue)
      * [`obj spec.components.env.valueFrom`](#obj-speccomponentsenvvaluefrom)
        * [`obj spec.components.env.valueFrom.configMapKeyRef`](#obj-speccomponentsenvvaluefromconfigmapkeyref)
          * [`fn withKey(key)`](#fn-speccomponentsenvvaluefromconfigmapkeyrefwithkey)
          * [`fn withName(name)`](#fn-speccomponentsenvvaluefromconfigmapkeyrefwithname)
          * [`fn withOptional(optional)`](#fn-speccomponentsenvvaluefromconfigmapkeyrefwithoptional)
        * [`obj spec.components.env.valueFrom.fieldRef`](#obj-speccomponentsenvvaluefromfieldref)
          * [`fn withApiVersion(apiVersion)`](#fn-speccomponentsenvvaluefromfieldrefwithapiversion)
          * [`fn withFieldPath(fieldPath)`](#fn-speccomponentsenvvaluefromfieldrefwithfieldpath)
        * [`obj spec.components.env.valueFrom.resourceFieldRef`](#obj-speccomponentsenvvaluefromresourcefieldref)
          * [`fn withContainerName(containerName)`](#fn-speccomponentsenvvaluefromresourcefieldrefwithcontainername)
          * [`fn withDivisor(divisor)`](#fn-speccomponentsenvvaluefromresourcefieldrefwithdivisor)
          * [`fn withResource(resource)`](#fn-speccomponentsenvvaluefromresourcefieldrefwithresource)
        * [`obj spec.components.env.valueFrom.secretKeyRef`](#obj-speccomponentsenvvaluefromsecretkeyref)
          * [`fn withKey(key)`](#fn-speccomponentsenvvaluefromsecretkeyrefwithkey)
          * [`fn withName(name)`](#fn-speccomponentsenvvaluefromsecretkeyrefwithname)
          * [`fn withOptional(optional)`](#fn-speccomponentsenvvaluefromsecretkeyrefwithoptional)
    * [`obj spec.components.imagePullSecrets`](#obj-speccomponentsimagepullsecrets)
      * [`fn withName(name)`](#fn-speccomponentsimagepullsecretswithname)
    * [`obj spec.components.indexCoord`](#obj-speccomponentsindexcoord)
      * [`fn withCommands(commands)`](#fn-speccomponentsindexcoordwithcommands)
      * [`fn withCommandsMixin(commands)`](#fn-speccomponentsindexcoordwithcommandsmixin)
      * [`fn withEnv(env)`](#fn-speccomponentsindexcoordwithenv)
      * [`fn withEnvMixin(env)`](#fn-speccomponentsindexcoordwithenvmixin)
      * [`fn withImage(image)`](#fn-speccomponentsindexcoordwithimage)
      * [`fn withImagePullPolicy(imagePullPolicy)`](#fn-speccomponentsindexcoordwithimagepullpolicy)
      * [`fn withImagePullSecrets(imagePullSecrets)`](#fn-speccomponentsindexcoordwithimagepullsecrets)
      * [`fn withImagePullSecretsMixin(imagePullSecrets)`](#fn-speccomponentsindexcoordwithimagepullsecretsmixin)
      * [`fn withInitContainers(initContainers)`](#fn-speccomponentsindexcoordwithinitcontainers)
      * [`fn withInitContainersMixin(initContainers)`](#fn-speccomponentsindexcoordwithinitcontainersmixin)
      * [`fn withNodeSelector(nodeSelector)`](#fn-speccomponentsindexcoordwithnodeselector)
      * [`fn withNodeSelectorMixin(nodeSelector)`](#fn-speccomponentsindexcoordwithnodeselectormixin)
      * [`fn withPaused(paused)`](#fn-speccomponentsindexcoordwithpaused)
      * [`fn withPodAnnotations(podAnnotations)`](#fn-speccomponentsindexcoordwithpodannotations)
      * [`fn withPodAnnotationsMixin(podAnnotations)`](#fn-speccomponentsindexcoordwithpodannotationsmixin)
      * [`fn withPodLabels(podLabels)`](#fn-speccomponentsindexcoordwithpodlabels)
      * [`fn withPodLabelsMixin(podLabels)`](#fn-speccomponentsindexcoordwithpodlabelsmixin)
      * [`fn withPort(port)`](#fn-speccomponentsindexcoordwithport)
      * [`fn withPriorityClassName(priorityClassName)`](#fn-speccomponentsindexcoordwithpriorityclassname)
      * [`fn withReplicas(replicas)`](#fn-speccomponentsindexcoordwithreplicas)
      * [`fn withRunWithSubProcess(runWithSubProcess)`](#fn-speccomponentsindexcoordwithrunwithsubprocess)
      * [`fn withSchedulerName(schedulerName)`](#fn-speccomponentsindexcoordwithschedulername)
      * [`fn withServiceAccountName(serviceAccountName)`](#fn-speccomponentsindexcoordwithserviceaccountname)
      * [`fn withSidecars(sidecars)`](#fn-speccomponentsindexcoordwithsidecars)
      * [`fn withSidecarsMixin(sidecars)`](#fn-speccomponentsindexcoordwithsidecarsmixin)
      * [`fn withTolerations(tolerations)`](#fn-speccomponentsindexcoordwithtolerations)
      * [`fn withTolerationsMixin(tolerations)`](#fn-speccomponentsindexcoordwithtolerationsmixin)
      * [`fn withVolumeMounts(volumeMounts)`](#fn-speccomponentsindexcoordwithvolumemounts)
      * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-speccomponentsindexcoordwithvolumemountsmixin)
      * [`fn withVolumes(volumes)`](#fn-speccomponentsindexcoordwithvolumes)
      * [`fn withVolumesMixin(volumes)`](#fn-speccomponentsindexcoordwithvolumesmixin)
      * [`obj spec.components.indexCoord.affinity`](#obj-speccomponentsindexcoordaffinity)
        * [`obj spec.components.indexCoord.affinity.nodeAffinity`](#obj-speccomponentsindexcoordaffinitynodeaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsindexcoordaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsindexcoordaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.components.indexCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsindexcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-speccomponentsindexcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.components.indexCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference`](#obj-speccomponentsindexcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreference)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsindexcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsindexcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressionsmixin)
              * [`fn withMatchFields(matchFields)`](#fn-speccomponentsindexcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfields)
              * [`fn withMatchFieldsMixin(matchFields)`](#fn-speccomponentsindexcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfieldsmixin)
              * [`obj spec.components.indexCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions`](#obj-speccomponentsindexcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsindexcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsindexcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsindexcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsindexcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvaluesmixin)
              * [`obj spec.components.indexCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields`](#obj-speccomponentsindexcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfields)
                * [`fn withKey(key)`](#fn-speccomponentsindexcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsindexcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsindexcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsindexcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvaluesmixin)
          * [`obj spec.components.indexCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsindexcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNodeSelectorTerms(nodeSelectorTerms)`](#fn-speccomponentsindexcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectorterms)
            * [`fn withNodeSelectorTermsMixin(nodeSelectorTerms)`](#fn-speccomponentsindexcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectortermsmixin)
            * [`obj spec.components.indexCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms`](#obj-speccomponentsindexcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectorterms)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsindexcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsindexcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressionsmixin)
              * [`fn withMatchFields(matchFields)`](#fn-speccomponentsindexcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfields)
              * [`fn withMatchFieldsMixin(matchFields)`](#fn-speccomponentsindexcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfieldsmixin)
              * [`obj spec.components.indexCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions`](#obj-speccomponentsindexcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsindexcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsindexcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsindexcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsindexcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvaluesmixin)
              * [`obj spec.components.indexCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields`](#obj-speccomponentsindexcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfields)
                * [`fn withKey(key)`](#fn-speccomponentsindexcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsindexcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsindexcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsindexcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvaluesmixin)
        * [`obj spec.components.indexCoord.affinity.podAffinity`](#obj-speccomponentsindexcoordaffinitypodaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsindexcoordaffinitypodaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsindexcoordaffinitypodaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsindexcoordaffinitypodaffinitywithrequiredduringschedulingignoredduringexecution)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsindexcoordaffinitypodaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsindexcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-speccomponentsindexcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-speccomponentsindexcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
              * [`fn withNamespaces(namespaces)`](#fn-speccomponentsindexcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
              * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsindexcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
              * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsindexcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
              * [`obj spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-speccomponentsindexcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsindexcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsindexcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsindexcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsindexcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                * [`obj spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-speccomponentsindexcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsindexcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsindexcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsindexcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsindexcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-speccomponentsindexcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsindexcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsindexcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsindexcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsindexcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                * [`obj spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-speccomponentsindexcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsindexcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsindexcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsindexcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsindexcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
          * [`obj spec.components.indexCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsindexcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNamespaces(namespaces)`](#fn-speccomponentsindexcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsindexcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsindexcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
            * [`obj spec.components.indexCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-speccomponentsindexcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsindexcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsindexcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsindexcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsindexcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
              * [`obj spec.components.indexCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-speccomponentsindexcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsindexcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsindexcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsindexcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsindexcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.components.indexCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-speccomponentsindexcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsindexcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsindexcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsindexcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsindexcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.components.indexCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-speccomponentsindexcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsindexcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsindexcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsindexcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsindexcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
        * [`obj spec.components.indexCoord.affinity.podAntiAffinity`](#obj-speccomponentsindexcoordaffinitypodantiaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsindexcoordaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsindexcoordaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsindexcoordaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecution)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsindexcoordaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsindexcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-speccomponentsindexcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-speccomponentsindexcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
              * [`fn withNamespaces(namespaces)`](#fn-speccomponentsindexcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
              * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsindexcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
              * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsindexcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
              * [`obj spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-speccomponentsindexcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsindexcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsindexcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsindexcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsindexcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                * [`obj spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-speccomponentsindexcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsindexcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsindexcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsindexcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsindexcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-speccomponentsindexcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsindexcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsindexcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsindexcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsindexcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                * [`obj spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-speccomponentsindexcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsindexcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsindexcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsindexcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsindexcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
          * [`obj spec.components.indexCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsindexcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNamespaces(namespaces)`](#fn-speccomponentsindexcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsindexcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsindexcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
            * [`obj spec.components.indexCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-speccomponentsindexcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsindexcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsindexcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsindexcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsindexcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
              * [`obj spec.components.indexCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-speccomponentsindexcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsindexcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsindexcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsindexcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsindexcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.components.indexCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-speccomponentsindexcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsindexcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsindexcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsindexcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsindexcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.components.indexCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-speccomponentsindexcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsindexcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsindexcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsindexcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsindexcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
      * [`obj spec.components.indexCoord.env`](#obj-speccomponentsindexcoordenv)
        * [`fn withName(name)`](#fn-speccomponentsindexcoordenvwithname)
        * [`fn withValue(value)`](#fn-speccomponentsindexcoordenvwithvalue)
        * [`obj spec.components.indexCoord.env.valueFrom`](#obj-speccomponentsindexcoordenvvaluefrom)
          * [`obj spec.components.indexCoord.env.valueFrom.configMapKeyRef`](#obj-speccomponentsindexcoordenvvaluefromconfigmapkeyref)
            * [`fn withKey(key)`](#fn-speccomponentsindexcoordenvvaluefromconfigmapkeyrefwithkey)
            * [`fn withName(name)`](#fn-speccomponentsindexcoordenvvaluefromconfigmapkeyrefwithname)
            * [`fn withOptional(optional)`](#fn-speccomponentsindexcoordenvvaluefromconfigmapkeyrefwithoptional)
          * [`obj spec.components.indexCoord.env.valueFrom.fieldRef`](#obj-speccomponentsindexcoordenvvaluefromfieldref)
            * [`fn withApiVersion(apiVersion)`](#fn-speccomponentsindexcoordenvvaluefromfieldrefwithapiversion)
            * [`fn withFieldPath(fieldPath)`](#fn-speccomponentsindexcoordenvvaluefromfieldrefwithfieldpath)
          * [`obj spec.components.indexCoord.env.valueFrom.resourceFieldRef`](#obj-speccomponentsindexcoordenvvaluefromresourcefieldref)
            * [`fn withContainerName(containerName)`](#fn-speccomponentsindexcoordenvvaluefromresourcefieldrefwithcontainername)
            * [`fn withDivisor(divisor)`](#fn-speccomponentsindexcoordenvvaluefromresourcefieldrefwithdivisor)
            * [`fn withResource(resource)`](#fn-speccomponentsindexcoordenvvaluefromresourcefieldrefwithresource)
          * [`obj spec.components.indexCoord.env.valueFrom.secretKeyRef`](#obj-speccomponentsindexcoordenvvaluefromsecretkeyref)
            * [`fn withKey(key)`](#fn-speccomponentsindexcoordenvvaluefromsecretkeyrefwithkey)
            * [`fn withName(name)`](#fn-speccomponentsindexcoordenvvaluefromsecretkeyrefwithname)
            * [`fn withOptional(optional)`](#fn-speccomponentsindexcoordenvvaluefromsecretkeyrefwithoptional)
      * [`obj spec.components.indexCoord.imagePullSecrets`](#obj-speccomponentsindexcoordimagepullsecrets)
        * [`fn withName(name)`](#fn-speccomponentsindexcoordimagepullsecretswithname)
      * [`obj spec.components.indexCoord.resources`](#obj-speccomponentsindexcoordresources)
        * [`fn withLimits(limits)`](#fn-speccomponentsindexcoordresourceswithlimits)
        * [`fn withLimitsMixin(limits)`](#fn-speccomponentsindexcoordresourceswithlimitsmixin)
        * [`fn withRequests(requests)`](#fn-speccomponentsindexcoordresourceswithrequests)
        * [`fn withRequestsMixin(requests)`](#fn-speccomponentsindexcoordresourceswithrequestsmixin)
      * [`obj spec.components.indexCoord.tolerations`](#obj-speccomponentsindexcoordtolerations)
        * [`fn withEffect(effect)`](#fn-speccomponentsindexcoordtolerationswitheffect)
        * [`fn withKey(key)`](#fn-speccomponentsindexcoordtolerationswithkey)
        * [`fn withOperator(operator)`](#fn-speccomponentsindexcoordtolerationswithoperator)
        * [`fn withTolerationSeconds(tolerationSeconds)`](#fn-speccomponentsindexcoordtolerationswithtolerationseconds)
        * [`fn withValue(value)`](#fn-speccomponentsindexcoordtolerationswithvalue)
      * [`obj spec.components.indexCoord.volumeMounts`](#obj-speccomponentsindexcoordvolumemounts)
        * [`fn withMountPath(mountPath)`](#fn-speccomponentsindexcoordvolumemountswithmountpath)
        * [`fn withMountPropagation(mountPropagation)`](#fn-speccomponentsindexcoordvolumemountswithmountpropagation)
        * [`fn withName(name)`](#fn-speccomponentsindexcoordvolumemountswithname)
        * [`fn withReadOnly(readOnly)`](#fn-speccomponentsindexcoordvolumemountswithreadonly)
        * [`fn withSubPath(subPath)`](#fn-speccomponentsindexcoordvolumemountswithsubpath)
        * [`fn withSubPathExpr(subPathExpr)`](#fn-speccomponentsindexcoordvolumemountswithsubpathexpr)
    * [`obj spec.components.indexNode`](#obj-speccomponentsindexnode)
      * [`fn withCommands(commands)`](#fn-speccomponentsindexnodewithcommands)
      * [`fn withCommandsMixin(commands)`](#fn-speccomponentsindexnodewithcommandsmixin)
      * [`fn withEnv(env)`](#fn-speccomponentsindexnodewithenv)
      * [`fn withEnvMixin(env)`](#fn-speccomponentsindexnodewithenvmixin)
      * [`fn withImage(image)`](#fn-speccomponentsindexnodewithimage)
      * [`fn withImagePullPolicy(imagePullPolicy)`](#fn-speccomponentsindexnodewithimagepullpolicy)
      * [`fn withImagePullSecrets(imagePullSecrets)`](#fn-speccomponentsindexnodewithimagepullsecrets)
      * [`fn withImagePullSecretsMixin(imagePullSecrets)`](#fn-speccomponentsindexnodewithimagepullsecretsmixin)
      * [`fn withInitContainers(initContainers)`](#fn-speccomponentsindexnodewithinitcontainers)
      * [`fn withInitContainersMixin(initContainers)`](#fn-speccomponentsindexnodewithinitcontainersmixin)
      * [`fn withNodeSelector(nodeSelector)`](#fn-speccomponentsindexnodewithnodeselector)
      * [`fn withNodeSelectorMixin(nodeSelector)`](#fn-speccomponentsindexnodewithnodeselectormixin)
      * [`fn withPaused(paused)`](#fn-speccomponentsindexnodewithpaused)
      * [`fn withPodAnnotations(podAnnotations)`](#fn-speccomponentsindexnodewithpodannotations)
      * [`fn withPodAnnotationsMixin(podAnnotations)`](#fn-speccomponentsindexnodewithpodannotationsmixin)
      * [`fn withPodLabels(podLabels)`](#fn-speccomponentsindexnodewithpodlabels)
      * [`fn withPodLabelsMixin(podLabels)`](#fn-speccomponentsindexnodewithpodlabelsmixin)
      * [`fn withPort(port)`](#fn-speccomponentsindexnodewithport)
      * [`fn withPriorityClassName(priorityClassName)`](#fn-speccomponentsindexnodewithpriorityclassname)
      * [`fn withReplicas(replicas)`](#fn-speccomponentsindexnodewithreplicas)
      * [`fn withRunWithSubProcess(runWithSubProcess)`](#fn-speccomponentsindexnodewithrunwithsubprocess)
      * [`fn withSchedulerName(schedulerName)`](#fn-speccomponentsindexnodewithschedulername)
      * [`fn withServiceAccountName(serviceAccountName)`](#fn-speccomponentsindexnodewithserviceaccountname)
      * [`fn withSidecars(sidecars)`](#fn-speccomponentsindexnodewithsidecars)
      * [`fn withSidecarsMixin(sidecars)`](#fn-speccomponentsindexnodewithsidecarsmixin)
      * [`fn withTolerations(tolerations)`](#fn-speccomponentsindexnodewithtolerations)
      * [`fn withTolerationsMixin(tolerations)`](#fn-speccomponentsindexnodewithtolerationsmixin)
      * [`fn withVolumeMounts(volumeMounts)`](#fn-speccomponentsindexnodewithvolumemounts)
      * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-speccomponentsindexnodewithvolumemountsmixin)
      * [`fn withVolumes(volumes)`](#fn-speccomponentsindexnodewithvolumes)
      * [`fn withVolumesMixin(volumes)`](#fn-speccomponentsindexnodewithvolumesmixin)
      * [`obj spec.components.indexNode.affinity`](#obj-speccomponentsindexnodeaffinity)
        * [`obj spec.components.indexNode.affinity.nodeAffinity`](#obj-speccomponentsindexnodeaffinitynodeaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsindexnodeaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsindexnodeaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.components.indexNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsindexnodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-speccomponentsindexnodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.components.indexNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference`](#obj-speccomponentsindexnodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreference)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsindexnodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsindexnodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressionsmixin)
              * [`fn withMatchFields(matchFields)`](#fn-speccomponentsindexnodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfields)
              * [`fn withMatchFieldsMixin(matchFields)`](#fn-speccomponentsindexnodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfieldsmixin)
              * [`obj spec.components.indexNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions`](#obj-speccomponentsindexnodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsindexnodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsindexnodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsindexnodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsindexnodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvaluesmixin)
              * [`obj spec.components.indexNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields`](#obj-speccomponentsindexnodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfields)
                * [`fn withKey(key)`](#fn-speccomponentsindexnodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsindexnodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsindexnodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsindexnodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvaluesmixin)
          * [`obj spec.components.indexNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsindexnodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNodeSelectorTerms(nodeSelectorTerms)`](#fn-speccomponentsindexnodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectorterms)
            * [`fn withNodeSelectorTermsMixin(nodeSelectorTerms)`](#fn-speccomponentsindexnodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectortermsmixin)
            * [`obj spec.components.indexNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms`](#obj-speccomponentsindexnodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectorterms)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsindexnodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsindexnodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressionsmixin)
              * [`fn withMatchFields(matchFields)`](#fn-speccomponentsindexnodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfields)
              * [`fn withMatchFieldsMixin(matchFields)`](#fn-speccomponentsindexnodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfieldsmixin)
              * [`obj spec.components.indexNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions`](#obj-speccomponentsindexnodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsindexnodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsindexnodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsindexnodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsindexnodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvaluesmixin)
              * [`obj spec.components.indexNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields`](#obj-speccomponentsindexnodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfields)
                * [`fn withKey(key)`](#fn-speccomponentsindexnodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsindexnodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsindexnodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsindexnodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvaluesmixin)
        * [`obj spec.components.indexNode.affinity.podAffinity`](#obj-speccomponentsindexnodeaffinitypodaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsindexnodeaffinitypodaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsindexnodeaffinitypodaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsindexnodeaffinitypodaffinitywithrequiredduringschedulingignoredduringexecution)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsindexnodeaffinitypodaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsindexnodeaffinitypodaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-speccomponentsindexnodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-speccomponentsindexnodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
              * [`fn withNamespaces(namespaces)`](#fn-speccomponentsindexnodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
              * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsindexnodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
              * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsindexnodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
              * [`obj spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-speccomponentsindexnodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsindexnodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsindexnodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsindexnodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsindexnodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                * [`obj spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-speccomponentsindexnodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsindexnodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsindexnodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsindexnodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsindexnodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-speccomponentsindexnodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsindexnodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsindexnodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsindexnodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsindexnodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                * [`obj spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-speccomponentsindexnodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsindexnodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsindexnodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsindexnodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsindexnodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
          * [`obj spec.components.indexNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsindexnodeaffinitypodaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNamespaces(namespaces)`](#fn-speccomponentsindexnodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsindexnodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsindexnodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
            * [`obj spec.components.indexNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-speccomponentsindexnodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsindexnodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsindexnodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsindexnodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsindexnodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
              * [`obj spec.components.indexNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-speccomponentsindexnodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsindexnodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsindexnodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsindexnodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsindexnodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.components.indexNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-speccomponentsindexnodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsindexnodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsindexnodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsindexnodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsindexnodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.components.indexNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-speccomponentsindexnodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsindexnodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsindexnodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsindexnodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsindexnodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
        * [`obj spec.components.indexNode.affinity.podAntiAffinity`](#obj-speccomponentsindexnodeaffinitypodantiaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsindexnodeaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsindexnodeaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsindexnodeaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecution)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsindexnodeaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsindexnodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-speccomponentsindexnodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-speccomponentsindexnodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
              * [`fn withNamespaces(namespaces)`](#fn-speccomponentsindexnodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
              * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsindexnodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
              * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsindexnodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
              * [`obj spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-speccomponentsindexnodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsindexnodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsindexnodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsindexnodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsindexnodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                * [`obj spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-speccomponentsindexnodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsindexnodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsindexnodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsindexnodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsindexnodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-speccomponentsindexnodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsindexnodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsindexnodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsindexnodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsindexnodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                * [`obj spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-speccomponentsindexnodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsindexnodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsindexnodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsindexnodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsindexnodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
          * [`obj spec.components.indexNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsindexnodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNamespaces(namespaces)`](#fn-speccomponentsindexnodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsindexnodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsindexnodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
            * [`obj spec.components.indexNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-speccomponentsindexnodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsindexnodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsindexnodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsindexnodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsindexnodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
              * [`obj spec.components.indexNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-speccomponentsindexnodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsindexnodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsindexnodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsindexnodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsindexnodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.components.indexNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-speccomponentsindexnodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsindexnodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsindexnodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsindexnodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsindexnodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.components.indexNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-speccomponentsindexnodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsindexnodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsindexnodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsindexnodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsindexnodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
      * [`obj spec.components.indexNode.env`](#obj-speccomponentsindexnodeenv)
        * [`fn withName(name)`](#fn-speccomponentsindexnodeenvwithname)
        * [`fn withValue(value)`](#fn-speccomponentsindexnodeenvwithvalue)
        * [`obj spec.components.indexNode.env.valueFrom`](#obj-speccomponentsindexnodeenvvaluefrom)
          * [`obj spec.components.indexNode.env.valueFrom.configMapKeyRef`](#obj-speccomponentsindexnodeenvvaluefromconfigmapkeyref)
            * [`fn withKey(key)`](#fn-speccomponentsindexnodeenvvaluefromconfigmapkeyrefwithkey)
            * [`fn withName(name)`](#fn-speccomponentsindexnodeenvvaluefromconfigmapkeyrefwithname)
            * [`fn withOptional(optional)`](#fn-speccomponentsindexnodeenvvaluefromconfigmapkeyrefwithoptional)
          * [`obj spec.components.indexNode.env.valueFrom.fieldRef`](#obj-speccomponentsindexnodeenvvaluefromfieldref)
            * [`fn withApiVersion(apiVersion)`](#fn-speccomponentsindexnodeenvvaluefromfieldrefwithapiversion)
            * [`fn withFieldPath(fieldPath)`](#fn-speccomponentsindexnodeenvvaluefromfieldrefwithfieldpath)
          * [`obj spec.components.indexNode.env.valueFrom.resourceFieldRef`](#obj-speccomponentsindexnodeenvvaluefromresourcefieldref)
            * [`fn withContainerName(containerName)`](#fn-speccomponentsindexnodeenvvaluefromresourcefieldrefwithcontainername)
            * [`fn withDivisor(divisor)`](#fn-speccomponentsindexnodeenvvaluefromresourcefieldrefwithdivisor)
            * [`fn withResource(resource)`](#fn-speccomponentsindexnodeenvvaluefromresourcefieldrefwithresource)
          * [`obj spec.components.indexNode.env.valueFrom.secretKeyRef`](#obj-speccomponentsindexnodeenvvaluefromsecretkeyref)
            * [`fn withKey(key)`](#fn-speccomponentsindexnodeenvvaluefromsecretkeyrefwithkey)
            * [`fn withName(name)`](#fn-speccomponentsindexnodeenvvaluefromsecretkeyrefwithname)
            * [`fn withOptional(optional)`](#fn-speccomponentsindexnodeenvvaluefromsecretkeyrefwithoptional)
      * [`obj spec.components.indexNode.imagePullSecrets`](#obj-speccomponentsindexnodeimagepullsecrets)
        * [`fn withName(name)`](#fn-speccomponentsindexnodeimagepullsecretswithname)
      * [`obj spec.components.indexNode.resources`](#obj-speccomponentsindexnoderesources)
        * [`fn withLimits(limits)`](#fn-speccomponentsindexnoderesourceswithlimits)
        * [`fn withLimitsMixin(limits)`](#fn-speccomponentsindexnoderesourceswithlimitsmixin)
        * [`fn withRequests(requests)`](#fn-speccomponentsindexnoderesourceswithrequests)
        * [`fn withRequestsMixin(requests)`](#fn-speccomponentsindexnoderesourceswithrequestsmixin)
      * [`obj spec.components.indexNode.tolerations`](#obj-speccomponentsindexnodetolerations)
        * [`fn withEffect(effect)`](#fn-speccomponentsindexnodetolerationswitheffect)
        * [`fn withKey(key)`](#fn-speccomponentsindexnodetolerationswithkey)
        * [`fn withOperator(operator)`](#fn-speccomponentsindexnodetolerationswithoperator)
        * [`fn withTolerationSeconds(tolerationSeconds)`](#fn-speccomponentsindexnodetolerationswithtolerationseconds)
        * [`fn withValue(value)`](#fn-speccomponentsindexnodetolerationswithvalue)
      * [`obj spec.components.indexNode.volumeMounts`](#obj-speccomponentsindexnodevolumemounts)
        * [`fn withMountPath(mountPath)`](#fn-speccomponentsindexnodevolumemountswithmountpath)
        * [`fn withMountPropagation(mountPropagation)`](#fn-speccomponentsindexnodevolumemountswithmountpropagation)
        * [`fn withName(name)`](#fn-speccomponentsindexnodevolumemountswithname)
        * [`fn withReadOnly(readOnly)`](#fn-speccomponentsindexnodevolumemountswithreadonly)
        * [`fn withSubPath(subPath)`](#fn-speccomponentsindexnodevolumemountswithsubpath)
        * [`fn withSubPathExpr(subPathExpr)`](#fn-speccomponentsindexnodevolumemountswithsubpathexpr)
    * [`obj spec.components.mixCoord`](#obj-speccomponentsmixcoord)
      * [`fn withCommands(commands)`](#fn-speccomponentsmixcoordwithcommands)
      * [`fn withCommandsMixin(commands)`](#fn-speccomponentsmixcoordwithcommandsmixin)
      * [`fn withEnv(env)`](#fn-speccomponentsmixcoordwithenv)
      * [`fn withEnvMixin(env)`](#fn-speccomponentsmixcoordwithenvmixin)
      * [`fn withImage(image)`](#fn-speccomponentsmixcoordwithimage)
      * [`fn withImagePullPolicy(imagePullPolicy)`](#fn-speccomponentsmixcoordwithimagepullpolicy)
      * [`fn withImagePullSecrets(imagePullSecrets)`](#fn-speccomponentsmixcoordwithimagepullsecrets)
      * [`fn withImagePullSecretsMixin(imagePullSecrets)`](#fn-speccomponentsmixcoordwithimagepullsecretsmixin)
      * [`fn withInitContainers(initContainers)`](#fn-speccomponentsmixcoordwithinitcontainers)
      * [`fn withInitContainersMixin(initContainers)`](#fn-speccomponentsmixcoordwithinitcontainersmixin)
      * [`fn withNodeSelector(nodeSelector)`](#fn-speccomponentsmixcoordwithnodeselector)
      * [`fn withNodeSelectorMixin(nodeSelector)`](#fn-speccomponentsmixcoordwithnodeselectormixin)
      * [`fn withPaused(paused)`](#fn-speccomponentsmixcoordwithpaused)
      * [`fn withPodAnnotations(podAnnotations)`](#fn-speccomponentsmixcoordwithpodannotations)
      * [`fn withPodAnnotationsMixin(podAnnotations)`](#fn-speccomponentsmixcoordwithpodannotationsmixin)
      * [`fn withPodLabels(podLabels)`](#fn-speccomponentsmixcoordwithpodlabels)
      * [`fn withPodLabelsMixin(podLabels)`](#fn-speccomponentsmixcoordwithpodlabelsmixin)
      * [`fn withPort(port)`](#fn-speccomponentsmixcoordwithport)
      * [`fn withPriorityClassName(priorityClassName)`](#fn-speccomponentsmixcoordwithpriorityclassname)
      * [`fn withReplicas(replicas)`](#fn-speccomponentsmixcoordwithreplicas)
      * [`fn withRunWithSubProcess(runWithSubProcess)`](#fn-speccomponentsmixcoordwithrunwithsubprocess)
      * [`fn withSchedulerName(schedulerName)`](#fn-speccomponentsmixcoordwithschedulername)
      * [`fn withServiceAccountName(serviceAccountName)`](#fn-speccomponentsmixcoordwithserviceaccountname)
      * [`fn withSidecars(sidecars)`](#fn-speccomponentsmixcoordwithsidecars)
      * [`fn withSidecarsMixin(sidecars)`](#fn-speccomponentsmixcoordwithsidecarsmixin)
      * [`fn withTolerations(tolerations)`](#fn-speccomponentsmixcoordwithtolerations)
      * [`fn withTolerationsMixin(tolerations)`](#fn-speccomponentsmixcoordwithtolerationsmixin)
      * [`fn withVolumeMounts(volumeMounts)`](#fn-speccomponentsmixcoordwithvolumemounts)
      * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-speccomponentsmixcoordwithvolumemountsmixin)
      * [`fn withVolumes(volumes)`](#fn-speccomponentsmixcoordwithvolumes)
      * [`fn withVolumesMixin(volumes)`](#fn-speccomponentsmixcoordwithvolumesmixin)
      * [`obj spec.components.mixCoord.affinity`](#obj-speccomponentsmixcoordaffinity)
        * [`obj spec.components.mixCoord.affinity.nodeAffinity`](#obj-speccomponentsmixcoordaffinitynodeaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsmixcoordaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsmixcoordaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.components.mixCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsmixcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-speccomponentsmixcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.components.mixCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference`](#obj-speccomponentsmixcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreference)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsmixcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsmixcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressionsmixin)
              * [`fn withMatchFields(matchFields)`](#fn-speccomponentsmixcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfields)
              * [`fn withMatchFieldsMixin(matchFields)`](#fn-speccomponentsmixcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfieldsmixin)
              * [`obj spec.components.mixCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions`](#obj-speccomponentsmixcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsmixcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsmixcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsmixcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsmixcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvaluesmixin)
              * [`obj spec.components.mixCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields`](#obj-speccomponentsmixcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfields)
                * [`fn withKey(key)`](#fn-speccomponentsmixcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsmixcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsmixcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsmixcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvaluesmixin)
          * [`obj spec.components.mixCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsmixcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNodeSelectorTerms(nodeSelectorTerms)`](#fn-speccomponentsmixcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectorterms)
            * [`fn withNodeSelectorTermsMixin(nodeSelectorTerms)`](#fn-speccomponentsmixcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectortermsmixin)
            * [`obj spec.components.mixCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms`](#obj-speccomponentsmixcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectorterms)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsmixcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsmixcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressionsmixin)
              * [`fn withMatchFields(matchFields)`](#fn-speccomponentsmixcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfields)
              * [`fn withMatchFieldsMixin(matchFields)`](#fn-speccomponentsmixcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfieldsmixin)
              * [`obj spec.components.mixCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions`](#obj-speccomponentsmixcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsmixcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsmixcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsmixcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsmixcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvaluesmixin)
              * [`obj spec.components.mixCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields`](#obj-speccomponentsmixcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfields)
                * [`fn withKey(key)`](#fn-speccomponentsmixcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsmixcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsmixcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsmixcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvaluesmixin)
        * [`obj spec.components.mixCoord.affinity.podAffinity`](#obj-speccomponentsmixcoordaffinitypodaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsmixcoordaffinitypodaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsmixcoordaffinitypodaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsmixcoordaffinitypodaffinitywithrequiredduringschedulingignoredduringexecution)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsmixcoordaffinitypodaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsmixcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-speccomponentsmixcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-speccomponentsmixcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
              * [`fn withNamespaces(namespaces)`](#fn-speccomponentsmixcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
              * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsmixcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
              * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsmixcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
              * [`obj spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-speccomponentsmixcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsmixcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsmixcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsmixcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsmixcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                * [`obj spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-speccomponentsmixcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsmixcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsmixcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsmixcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsmixcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-speccomponentsmixcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsmixcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsmixcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsmixcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsmixcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                * [`obj spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-speccomponentsmixcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsmixcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsmixcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsmixcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsmixcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
          * [`obj spec.components.mixCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsmixcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNamespaces(namespaces)`](#fn-speccomponentsmixcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsmixcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsmixcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
            * [`obj spec.components.mixCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-speccomponentsmixcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsmixcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsmixcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsmixcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsmixcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
              * [`obj spec.components.mixCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-speccomponentsmixcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsmixcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsmixcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsmixcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsmixcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.components.mixCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-speccomponentsmixcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsmixcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsmixcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsmixcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsmixcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.components.mixCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-speccomponentsmixcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsmixcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsmixcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsmixcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsmixcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
        * [`obj spec.components.mixCoord.affinity.podAntiAffinity`](#obj-speccomponentsmixcoordaffinitypodantiaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsmixcoordaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsmixcoordaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsmixcoordaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecution)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsmixcoordaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsmixcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-speccomponentsmixcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-speccomponentsmixcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
              * [`fn withNamespaces(namespaces)`](#fn-speccomponentsmixcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
              * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsmixcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
              * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsmixcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
              * [`obj spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-speccomponentsmixcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsmixcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsmixcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsmixcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsmixcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                * [`obj spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-speccomponentsmixcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsmixcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsmixcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsmixcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsmixcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-speccomponentsmixcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsmixcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsmixcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsmixcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsmixcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                * [`obj spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-speccomponentsmixcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsmixcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsmixcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsmixcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsmixcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
          * [`obj spec.components.mixCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsmixcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNamespaces(namespaces)`](#fn-speccomponentsmixcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsmixcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsmixcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
            * [`obj spec.components.mixCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-speccomponentsmixcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsmixcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsmixcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsmixcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsmixcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
              * [`obj spec.components.mixCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-speccomponentsmixcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsmixcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsmixcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsmixcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsmixcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.components.mixCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-speccomponentsmixcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsmixcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsmixcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsmixcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsmixcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.components.mixCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-speccomponentsmixcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsmixcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsmixcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsmixcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsmixcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
      * [`obj spec.components.mixCoord.env`](#obj-speccomponentsmixcoordenv)
        * [`fn withName(name)`](#fn-speccomponentsmixcoordenvwithname)
        * [`fn withValue(value)`](#fn-speccomponentsmixcoordenvwithvalue)
        * [`obj spec.components.mixCoord.env.valueFrom`](#obj-speccomponentsmixcoordenvvaluefrom)
          * [`obj spec.components.mixCoord.env.valueFrom.configMapKeyRef`](#obj-speccomponentsmixcoordenvvaluefromconfigmapkeyref)
            * [`fn withKey(key)`](#fn-speccomponentsmixcoordenvvaluefromconfigmapkeyrefwithkey)
            * [`fn withName(name)`](#fn-speccomponentsmixcoordenvvaluefromconfigmapkeyrefwithname)
            * [`fn withOptional(optional)`](#fn-speccomponentsmixcoordenvvaluefromconfigmapkeyrefwithoptional)
          * [`obj spec.components.mixCoord.env.valueFrom.fieldRef`](#obj-speccomponentsmixcoordenvvaluefromfieldref)
            * [`fn withApiVersion(apiVersion)`](#fn-speccomponentsmixcoordenvvaluefromfieldrefwithapiversion)
            * [`fn withFieldPath(fieldPath)`](#fn-speccomponentsmixcoordenvvaluefromfieldrefwithfieldpath)
          * [`obj spec.components.mixCoord.env.valueFrom.resourceFieldRef`](#obj-speccomponentsmixcoordenvvaluefromresourcefieldref)
            * [`fn withContainerName(containerName)`](#fn-speccomponentsmixcoordenvvaluefromresourcefieldrefwithcontainername)
            * [`fn withDivisor(divisor)`](#fn-speccomponentsmixcoordenvvaluefromresourcefieldrefwithdivisor)
            * [`fn withResource(resource)`](#fn-speccomponentsmixcoordenvvaluefromresourcefieldrefwithresource)
          * [`obj spec.components.mixCoord.env.valueFrom.secretKeyRef`](#obj-speccomponentsmixcoordenvvaluefromsecretkeyref)
            * [`fn withKey(key)`](#fn-speccomponentsmixcoordenvvaluefromsecretkeyrefwithkey)
            * [`fn withName(name)`](#fn-speccomponentsmixcoordenvvaluefromsecretkeyrefwithname)
            * [`fn withOptional(optional)`](#fn-speccomponentsmixcoordenvvaluefromsecretkeyrefwithoptional)
      * [`obj spec.components.mixCoord.imagePullSecrets`](#obj-speccomponentsmixcoordimagepullsecrets)
        * [`fn withName(name)`](#fn-speccomponentsmixcoordimagepullsecretswithname)
      * [`obj spec.components.mixCoord.resources`](#obj-speccomponentsmixcoordresources)
        * [`fn withLimits(limits)`](#fn-speccomponentsmixcoordresourceswithlimits)
        * [`fn withLimitsMixin(limits)`](#fn-speccomponentsmixcoordresourceswithlimitsmixin)
        * [`fn withRequests(requests)`](#fn-speccomponentsmixcoordresourceswithrequests)
        * [`fn withRequestsMixin(requests)`](#fn-speccomponentsmixcoordresourceswithrequestsmixin)
      * [`obj spec.components.mixCoord.tolerations`](#obj-speccomponentsmixcoordtolerations)
        * [`fn withEffect(effect)`](#fn-speccomponentsmixcoordtolerationswitheffect)
        * [`fn withKey(key)`](#fn-speccomponentsmixcoordtolerationswithkey)
        * [`fn withOperator(operator)`](#fn-speccomponentsmixcoordtolerationswithoperator)
        * [`fn withTolerationSeconds(tolerationSeconds)`](#fn-speccomponentsmixcoordtolerationswithtolerationseconds)
        * [`fn withValue(value)`](#fn-speccomponentsmixcoordtolerationswithvalue)
      * [`obj spec.components.mixCoord.volumeMounts`](#obj-speccomponentsmixcoordvolumemounts)
        * [`fn withMountPath(mountPath)`](#fn-speccomponentsmixcoordvolumemountswithmountpath)
        * [`fn withMountPropagation(mountPropagation)`](#fn-speccomponentsmixcoordvolumemountswithmountpropagation)
        * [`fn withName(name)`](#fn-speccomponentsmixcoordvolumemountswithname)
        * [`fn withReadOnly(readOnly)`](#fn-speccomponentsmixcoordvolumemountswithreadonly)
        * [`fn withSubPath(subPath)`](#fn-speccomponentsmixcoordvolumemountswithsubpath)
        * [`fn withSubPathExpr(subPathExpr)`](#fn-speccomponentsmixcoordvolumemountswithsubpathexpr)
    * [`obj spec.components.proxy`](#obj-speccomponentsproxy)
      * [`fn withCommands(commands)`](#fn-speccomponentsproxywithcommands)
      * [`fn withCommandsMixin(commands)`](#fn-speccomponentsproxywithcommandsmixin)
      * [`fn withEnv(env)`](#fn-speccomponentsproxywithenv)
      * [`fn withEnvMixin(env)`](#fn-speccomponentsproxywithenvmixin)
      * [`fn withImage(image)`](#fn-speccomponentsproxywithimage)
      * [`fn withImagePullPolicy(imagePullPolicy)`](#fn-speccomponentsproxywithimagepullpolicy)
      * [`fn withImagePullSecrets(imagePullSecrets)`](#fn-speccomponentsproxywithimagepullsecrets)
      * [`fn withImagePullSecretsMixin(imagePullSecrets)`](#fn-speccomponentsproxywithimagepullsecretsmixin)
      * [`fn withInitContainers(initContainers)`](#fn-speccomponentsproxywithinitcontainers)
      * [`fn withInitContainersMixin(initContainers)`](#fn-speccomponentsproxywithinitcontainersmixin)
      * [`fn withNodeSelector(nodeSelector)`](#fn-speccomponentsproxywithnodeselector)
      * [`fn withNodeSelectorMixin(nodeSelector)`](#fn-speccomponentsproxywithnodeselectormixin)
      * [`fn withPaused(paused)`](#fn-speccomponentsproxywithpaused)
      * [`fn withPodAnnotations(podAnnotations)`](#fn-speccomponentsproxywithpodannotations)
      * [`fn withPodAnnotationsMixin(podAnnotations)`](#fn-speccomponentsproxywithpodannotationsmixin)
      * [`fn withPodLabels(podLabels)`](#fn-speccomponentsproxywithpodlabels)
      * [`fn withPodLabelsMixin(podLabels)`](#fn-speccomponentsproxywithpodlabelsmixin)
      * [`fn withPort(port)`](#fn-speccomponentsproxywithport)
      * [`fn withPriorityClassName(priorityClassName)`](#fn-speccomponentsproxywithpriorityclassname)
      * [`fn withReplicas(replicas)`](#fn-speccomponentsproxywithreplicas)
      * [`fn withRunWithSubProcess(runWithSubProcess)`](#fn-speccomponentsproxywithrunwithsubprocess)
      * [`fn withSchedulerName(schedulerName)`](#fn-speccomponentsproxywithschedulername)
      * [`fn withServiceAccountName(serviceAccountName)`](#fn-speccomponentsproxywithserviceaccountname)
      * [`fn withServiceAnnotations(serviceAnnotations)`](#fn-speccomponentsproxywithserviceannotations)
      * [`fn withServiceAnnotationsMixin(serviceAnnotations)`](#fn-speccomponentsproxywithserviceannotationsmixin)
      * [`fn withServiceLabels(serviceLabels)`](#fn-speccomponentsproxywithservicelabels)
      * [`fn withServiceLabelsMixin(serviceLabels)`](#fn-speccomponentsproxywithservicelabelsmixin)
      * [`fn withServiceRestfulPort(serviceRestfulPort)`](#fn-speccomponentsproxywithservicerestfulport)
      * [`fn withServiceType(serviceType)`](#fn-speccomponentsproxywithservicetype)
      * [`fn withSidecars(sidecars)`](#fn-speccomponentsproxywithsidecars)
      * [`fn withSidecarsMixin(sidecars)`](#fn-speccomponentsproxywithsidecarsmixin)
      * [`fn withTolerations(tolerations)`](#fn-speccomponentsproxywithtolerations)
      * [`fn withTolerationsMixin(tolerations)`](#fn-speccomponentsproxywithtolerationsmixin)
      * [`fn withVolumeMounts(volumeMounts)`](#fn-speccomponentsproxywithvolumemounts)
      * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-speccomponentsproxywithvolumemountsmixin)
      * [`fn withVolumes(volumes)`](#fn-speccomponentsproxywithvolumes)
      * [`fn withVolumesMixin(volumes)`](#fn-speccomponentsproxywithvolumesmixin)
      * [`obj spec.components.proxy.affinity`](#obj-speccomponentsproxyaffinity)
        * [`obj spec.components.proxy.affinity.nodeAffinity`](#obj-speccomponentsproxyaffinitynodeaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsproxyaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsproxyaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.components.proxy.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsproxyaffinitynodeaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-speccomponentsproxyaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.components.proxy.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference`](#obj-speccomponentsproxyaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreference)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsproxyaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsproxyaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressionsmixin)
              * [`fn withMatchFields(matchFields)`](#fn-speccomponentsproxyaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfields)
              * [`fn withMatchFieldsMixin(matchFields)`](#fn-speccomponentsproxyaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfieldsmixin)
              * [`obj spec.components.proxy.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions`](#obj-speccomponentsproxyaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsproxyaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsproxyaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsproxyaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsproxyaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvaluesmixin)
              * [`obj spec.components.proxy.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields`](#obj-speccomponentsproxyaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfields)
                * [`fn withKey(key)`](#fn-speccomponentsproxyaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsproxyaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsproxyaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsproxyaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvaluesmixin)
          * [`obj spec.components.proxy.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsproxyaffinitynodeaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNodeSelectorTerms(nodeSelectorTerms)`](#fn-speccomponentsproxyaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectorterms)
            * [`fn withNodeSelectorTermsMixin(nodeSelectorTerms)`](#fn-speccomponentsproxyaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectortermsmixin)
            * [`obj spec.components.proxy.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms`](#obj-speccomponentsproxyaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectorterms)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsproxyaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsproxyaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressionsmixin)
              * [`fn withMatchFields(matchFields)`](#fn-speccomponentsproxyaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfields)
              * [`fn withMatchFieldsMixin(matchFields)`](#fn-speccomponentsproxyaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfieldsmixin)
              * [`obj spec.components.proxy.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions`](#obj-speccomponentsproxyaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsproxyaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsproxyaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsproxyaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsproxyaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvaluesmixin)
              * [`obj spec.components.proxy.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields`](#obj-speccomponentsproxyaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfields)
                * [`fn withKey(key)`](#fn-speccomponentsproxyaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsproxyaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsproxyaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsproxyaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvaluesmixin)
        * [`obj spec.components.proxy.affinity.podAffinity`](#obj-speccomponentsproxyaffinitypodaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsproxyaffinitypodaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsproxyaffinitypodaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsproxyaffinitypodaffinitywithrequiredduringschedulingignoredduringexecution)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsproxyaffinitypodaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsproxyaffinitypodaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-speccomponentsproxyaffinitypodaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-speccomponentsproxyaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
              * [`fn withNamespaces(namespaces)`](#fn-speccomponentsproxyaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
              * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsproxyaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
              * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsproxyaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
              * [`obj spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-speccomponentsproxyaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsproxyaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsproxyaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsproxyaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsproxyaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                * [`obj spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-speccomponentsproxyaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsproxyaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsproxyaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsproxyaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsproxyaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-speccomponentsproxyaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsproxyaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsproxyaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsproxyaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsproxyaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                * [`obj spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-speccomponentsproxyaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsproxyaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsproxyaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsproxyaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsproxyaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
          * [`obj spec.components.proxy.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsproxyaffinitypodaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNamespaces(namespaces)`](#fn-speccomponentsproxyaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsproxyaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsproxyaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
            * [`obj spec.components.proxy.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-speccomponentsproxyaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsproxyaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsproxyaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsproxyaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsproxyaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
              * [`obj spec.components.proxy.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-speccomponentsproxyaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsproxyaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsproxyaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsproxyaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsproxyaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.components.proxy.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-speccomponentsproxyaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsproxyaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsproxyaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsproxyaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsproxyaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.components.proxy.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-speccomponentsproxyaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsproxyaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsproxyaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsproxyaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsproxyaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
        * [`obj spec.components.proxy.affinity.podAntiAffinity`](#obj-speccomponentsproxyaffinitypodantiaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsproxyaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsproxyaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsproxyaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecution)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsproxyaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsproxyaffinitypodantiaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-speccomponentsproxyaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-speccomponentsproxyaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
              * [`fn withNamespaces(namespaces)`](#fn-speccomponentsproxyaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
              * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsproxyaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
              * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsproxyaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
              * [`obj spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-speccomponentsproxyaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsproxyaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsproxyaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsproxyaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsproxyaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                * [`obj spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-speccomponentsproxyaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsproxyaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsproxyaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsproxyaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsproxyaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-speccomponentsproxyaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsproxyaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsproxyaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsproxyaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsproxyaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                * [`obj spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-speccomponentsproxyaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsproxyaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsproxyaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsproxyaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsproxyaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
          * [`obj spec.components.proxy.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsproxyaffinitypodantiaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNamespaces(namespaces)`](#fn-speccomponentsproxyaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsproxyaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsproxyaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
            * [`obj spec.components.proxy.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-speccomponentsproxyaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsproxyaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsproxyaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsproxyaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsproxyaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
              * [`obj spec.components.proxy.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-speccomponentsproxyaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsproxyaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsproxyaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsproxyaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsproxyaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.components.proxy.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-speccomponentsproxyaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsproxyaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsproxyaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsproxyaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsproxyaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.components.proxy.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-speccomponentsproxyaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsproxyaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsproxyaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsproxyaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsproxyaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
      * [`obj spec.components.proxy.env`](#obj-speccomponentsproxyenv)
        * [`fn withName(name)`](#fn-speccomponentsproxyenvwithname)
        * [`fn withValue(value)`](#fn-speccomponentsproxyenvwithvalue)
        * [`obj spec.components.proxy.env.valueFrom`](#obj-speccomponentsproxyenvvaluefrom)
          * [`obj spec.components.proxy.env.valueFrom.configMapKeyRef`](#obj-speccomponentsproxyenvvaluefromconfigmapkeyref)
            * [`fn withKey(key)`](#fn-speccomponentsproxyenvvaluefromconfigmapkeyrefwithkey)
            * [`fn withName(name)`](#fn-speccomponentsproxyenvvaluefromconfigmapkeyrefwithname)
            * [`fn withOptional(optional)`](#fn-speccomponentsproxyenvvaluefromconfigmapkeyrefwithoptional)
          * [`obj spec.components.proxy.env.valueFrom.fieldRef`](#obj-speccomponentsproxyenvvaluefromfieldref)
            * [`fn withApiVersion(apiVersion)`](#fn-speccomponentsproxyenvvaluefromfieldrefwithapiversion)
            * [`fn withFieldPath(fieldPath)`](#fn-speccomponentsproxyenvvaluefromfieldrefwithfieldpath)
          * [`obj spec.components.proxy.env.valueFrom.resourceFieldRef`](#obj-speccomponentsproxyenvvaluefromresourcefieldref)
            * [`fn withContainerName(containerName)`](#fn-speccomponentsproxyenvvaluefromresourcefieldrefwithcontainername)
            * [`fn withDivisor(divisor)`](#fn-speccomponentsproxyenvvaluefromresourcefieldrefwithdivisor)
            * [`fn withResource(resource)`](#fn-speccomponentsproxyenvvaluefromresourcefieldrefwithresource)
          * [`obj spec.components.proxy.env.valueFrom.secretKeyRef`](#obj-speccomponentsproxyenvvaluefromsecretkeyref)
            * [`fn withKey(key)`](#fn-speccomponentsproxyenvvaluefromsecretkeyrefwithkey)
            * [`fn withName(name)`](#fn-speccomponentsproxyenvvaluefromsecretkeyrefwithname)
            * [`fn withOptional(optional)`](#fn-speccomponentsproxyenvvaluefromsecretkeyrefwithoptional)
      * [`obj spec.components.proxy.imagePullSecrets`](#obj-speccomponentsproxyimagepullsecrets)
        * [`fn withName(name)`](#fn-speccomponentsproxyimagepullsecretswithname)
      * [`obj spec.components.proxy.ingress`](#obj-speccomponentsproxyingress)
        * [`fn withAnnotations(annotations)`](#fn-speccomponentsproxyingresswithannotations)
        * [`fn withAnnotationsMixin(annotations)`](#fn-speccomponentsproxyingresswithannotationsmixin)
        * [`fn withHosts(hosts)`](#fn-speccomponentsproxyingresswithhosts)
        * [`fn withHostsMixin(hosts)`](#fn-speccomponentsproxyingresswithhostsmixin)
        * [`fn withIngressClassName(ingressClassName)`](#fn-speccomponentsproxyingresswithingressclassname)
        * [`fn withLabels(labels)`](#fn-speccomponentsproxyingresswithlabels)
        * [`fn withLabelsMixin(labels)`](#fn-speccomponentsproxyingresswithlabelsmixin)
        * [`fn withTlsSecretRefs(tlsSecretRefs)`](#fn-speccomponentsproxyingresswithtlssecretrefs)
        * [`fn withTlsSecretRefsMixin(tlsSecretRefs)`](#fn-speccomponentsproxyingresswithtlssecretrefsmixin)
      * [`obj spec.components.proxy.resources`](#obj-speccomponentsproxyresources)
        * [`fn withLimits(limits)`](#fn-speccomponentsproxyresourceswithlimits)
        * [`fn withLimitsMixin(limits)`](#fn-speccomponentsproxyresourceswithlimitsmixin)
        * [`fn withRequests(requests)`](#fn-speccomponentsproxyresourceswithrequests)
        * [`fn withRequestsMixin(requests)`](#fn-speccomponentsproxyresourceswithrequestsmixin)
      * [`obj spec.components.proxy.tolerations`](#obj-speccomponentsproxytolerations)
        * [`fn withEffect(effect)`](#fn-speccomponentsproxytolerationswitheffect)
        * [`fn withKey(key)`](#fn-speccomponentsproxytolerationswithkey)
        * [`fn withOperator(operator)`](#fn-speccomponentsproxytolerationswithoperator)
        * [`fn withTolerationSeconds(tolerationSeconds)`](#fn-speccomponentsproxytolerationswithtolerationseconds)
        * [`fn withValue(value)`](#fn-speccomponentsproxytolerationswithvalue)
      * [`obj spec.components.proxy.volumeMounts`](#obj-speccomponentsproxyvolumemounts)
        * [`fn withMountPath(mountPath)`](#fn-speccomponentsproxyvolumemountswithmountpath)
        * [`fn withMountPropagation(mountPropagation)`](#fn-speccomponentsproxyvolumemountswithmountpropagation)
        * [`fn withName(name)`](#fn-speccomponentsproxyvolumemountswithname)
        * [`fn withReadOnly(readOnly)`](#fn-speccomponentsproxyvolumemountswithreadonly)
        * [`fn withSubPath(subPath)`](#fn-speccomponentsproxyvolumemountswithsubpath)
        * [`fn withSubPathExpr(subPathExpr)`](#fn-speccomponentsproxyvolumemountswithsubpathexpr)
    * [`obj spec.components.queryCoord`](#obj-speccomponentsquerycoord)
      * [`fn withCommands(commands)`](#fn-speccomponentsquerycoordwithcommands)
      * [`fn withCommandsMixin(commands)`](#fn-speccomponentsquerycoordwithcommandsmixin)
      * [`fn withEnv(env)`](#fn-speccomponentsquerycoordwithenv)
      * [`fn withEnvMixin(env)`](#fn-speccomponentsquerycoordwithenvmixin)
      * [`fn withImage(image)`](#fn-speccomponentsquerycoordwithimage)
      * [`fn withImagePullPolicy(imagePullPolicy)`](#fn-speccomponentsquerycoordwithimagepullpolicy)
      * [`fn withImagePullSecrets(imagePullSecrets)`](#fn-speccomponentsquerycoordwithimagepullsecrets)
      * [`fn withImagePullSecretsMixin(imagePullSecrets)`](#fn-speccomponentsquerycoordwithimagepullsecretsmixin)
      * [`fn withInitContainers(initContainers)`](#fn-speccomponentsquerycoordwithinitcontainers)
      * [`fn withInitContainersMixin(initContainers)`](#fn-speccomponentsquerycoordwithinitcontainersmixin)
      * [`fn withNodeSelector(nodeSelector)`](#fn-speccomponentsquerycoordwithnodeselector)
      * [`fn withNodeSelectorMixin(nodeSelector)`](#fn-speccomponentsquerycoordwithnodeselectormixin)
      * [`fn withPaused(paused)`](#fn-speccomponentsquerycoordwithpaused)
      * [`fn withPodAnnotations(podAnnotations)`](#fn-speccomponentsquerycoordwithpodannotations)
      * [`fn withPodAnnotationsMixin(podAnnotations)`](#fn-speccomponentsquerycoordwithpodannotationsmixin)
      * [`fn withPodLabels(podLabels)`](#fn-speccomponentsquerycoordwithpodlabels)
      * [`fn withPodLabelsMixin(podLabels)`](#fn-speccomponentsquerycoordwithpodlabelsmixin)
      * [`fn withPort(port)`](#fn-speccomponentsquerycoordwithport)
      * [`fn withPriorityClassName(priorityClassName)`](#fn-speccomponentsquerycoordwithpriorityclassname)
      * [`fn withReplicas(replicas)`](#fn-speccomponentsquerycoordwithreplicas)
      * [`fn withRunWithSubProcess(runWithSubProcess)`](#fn-speccomponentsquerycoordwithrunwithsubprocess)
      * [`fn withSchedulerName(schedulerName)`](#fn-speccomponentsquerycoordwithschedulername)
      * [`fn withServiceAccountName(serviceAccountName)`](#fn-speccomponentsquerycoordwithserviceaccountname)
      * [`fn withSidecars(sidecars)`](#fn-speccomponentsquerycoordwithsidecars)
      * [`fn withSidecarsMixin(sidecars)`](#fn-speccomponentsquerycoordwithsidecarsmixin)
      * [`fn withTolerations(tolerations)`](#fn-speccomponentsquerycoordwithtolerations)
      * [`fn withTolerationsMixin(tolerations)`](#fn-speccomponentsquerycoordwithtolerationsmixin)
      * [`fn withVolumeMounts(volumeMounts)`](#fn-speccomponentsquerycoordwithvolumemounts)
      * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-speccomponentsquerycoordwithvolumemountsmixin)
      * [`fn withVolumes(volumes)`](#fn-speccomponentsquerycoordwithvolumes)
      * [`fn withVolumesMixin(volumes)`](#fn-speccomponentsquerycoordwithvolumesmixin)
      * [`obj spec.components.queryCoord.affinity`](#obj-speccomponentsquerycoordaffinity)
        * [`obj spec.components.queryCoord.affinity.nodeAffinity`](#obj-speccomponentsquerycoordaffinitynodeaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsquerycoordaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsquerycoordaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.components.queryCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsquerycoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-speccomponentsquerycoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.components.queryCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference`](#obj-speccomponentsquerycoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreference)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsquerycoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsquerycoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressionsmixin)
              * [`fn withMatchFields(matchFields)`](#fn-speccomponentsquerycoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfields)
              * [`fn withMatchFieldsMixin(matchFields)`](#fn-speccomponentsquerycoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfieldsmixin)
              * [`obj spec.components.queryCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions`](#obj-speccomponentsquerycoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsquerycoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsquerycoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsquerycoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsquerycoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvaluesmixin)
              * [`obj spec.components.queryCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields`](#obj-speccomponentsquerycoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfields)
                * [`fn withKey(key)`](#fn-speccomponentsquerycoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsquerycoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsquerycoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsquerycoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvaluesmixin)
          * [`obj spec.components.queryCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsquerycoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNodeSelectorTerms(nodeSelectorTerms)`](#fn-speccomponentsquerycoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectorterms)
            * [`fn withNodeSelectorTermsMixin(nodeSelectorTerms)`](#fn-speccomponentsquerycoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectortermsmixin)
            * [`obj spec.components.queryCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms`](#obj-speccomponentsquerycoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectorterms)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsquerycoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsquerycoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressionsmixin)
              * [`fn withMatchFields(matchFields)`](#fn-speccomponentsquerycoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfields)
              * [`fn withMatchFieldsMixin(matchFields)`](#fn-speccomponentsquerycoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfieldsmixin)
              * [`obj spec.components.queryCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions`](#obj-speccomponentsquerycoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsquerycoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsquerycoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsquerycoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsquerycoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvaluesmixin)
              * [`obj spec.components.queryCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields`](#obj-speccomponentsquerycoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfields)
                * [`fn withKey(key)`](#fn-speccomponentsquerycoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsquerycoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsquerycoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsquerycoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvaluesmixin)
        * [`obj spec.components.queryCoord.affinity.podAffinity`](#obj-speccomponentsquerycoordaffinitypodaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsquerycoordaffinitypodaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsquerycoordaffinitypodaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsquerycoordaffinitypodaffinitywithrequiredduringschedulingignoredduringexecution)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsquerycoordaffinitypodaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsquerycoordaffinitypodaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-speccomponentsquerycoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-speccomponentsquerycoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
              * [`fn withNamespaces(namespaces)`](#fn-speccomponentsquerycoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
              * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsquerycoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
              * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsquerycoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
              * [`obj spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-speccomponentsquerycoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsquerycoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsquerycoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsquerycoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsquerycoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                * [`obj spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-speccomponentsquerycoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsquerycoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsquerycoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsquerycoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsquerycoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-speccomponentsquerycoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsquerycoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsquerycoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsquerycoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsquerycoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                * [`obj spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-speccomponentsquerycoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsquerycoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsquerycoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsquerycoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsquerycoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
          * [`obj spec.components.queryCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsquerycoordaffinitypodaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNamespaces(namespaces)`](#fn-speccomponentsquerycoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsquerycoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsquerycoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
            * [`obj spec.components.queryCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-speccomponentsquerycoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsquerycoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsquerycoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsquerycoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsquerycoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
              * [`obj spec.components.queryCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-speccomponentsquerycoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsquerycoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsquerycoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsquerycoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsquerycoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.components.queryCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-speccomponentsquerycoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsquerycoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsquerycoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsquerycoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsquerycoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.components.queryCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-speccomponentsquerycoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsquerycoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsquerycoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsquerycoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsquerycoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
        * [`obj spec.components.queryCoord.affinity.podAntiAffinity`](#obj-speccomponentsquerycoordaffinitypodantiaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsquerycoordaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsquerycoordaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsquerycoordaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecution)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsquerycoordaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsquerycoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-speccomponentsquerycoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-speccomponentsquerycoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
              * [`fn withNamespaces(namespaces)`](#fn-speccomponentsquerycoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
              * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsquerycoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
              * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsquerycoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
              * [`obj spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-speccomponentsquerycoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsquerycoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsquerycoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsquerycoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsquerycoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                * [`obj spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-speccomponentsquerycoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsquerycoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsquerycoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsquerycoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsquerycoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-speccomponentsquerycoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsquerycoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsquerycoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsquerycoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsquerycoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                * [`obj spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-speccomponentsquerycoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsquerycoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsquerycoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsquerycoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsquerycoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
          * [`obj spec.components.queryCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsquerycoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNamespaces(namespaces)`](#fn-speccomponentsquerycoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsquerycoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsquerycoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
            * [`obj spec.components.queryCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-speccomponentsquerycoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsquerycoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsquerycoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsquerycoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsquerycoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
              * [`obj spec.components.queryCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-speccomponentsquerycoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsquerycoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsquerycoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsquerycoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsquerycoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.components.queryCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-speccomponentsquerycoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsquerycoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsquerycoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsquerycoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsquerycoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.components.queryCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-speccomponentsquerycoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsquerycoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsquerycoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsquerycoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsquerycoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
      * [`obj spec.components.queryCoord.env`](#obj-speccomponentsquerycoordenv)
        * [`fn withName(name)`](#fn-speccomponentsquerycoordenvwithname)
        * [`fn withValue(value)`](#fn-speccomponentsquerycoordenvwithvalue)
        * [`obj spec.components.queryCoord.env.valueFrom`](#obj-speccomponentsquerycoordenvvaluefrom)
          * [`obj spec.components.queryCoord.env.valueFrom.configMapKeyRef`](#obj-speccomponentsquerycoordenvvaluefromconfigmapkeyref)
            * [`fn withKey(key)`](#fn-speccomponentsquerycoordenvvaluefromconfigmapkeyrefwithkey)
            * [`fn withName(name)`](#fn-speccomponentsquerycoordenvvaluefromconfigmapkeyrefwithname)
            * [`fn withOptional(optional)`](#fn-speccomponentsquerycoordenvvaluefromconfigmapkeyrefwithoptional)
          * [`obj spec.components.queryCoord.env.valueFrom.fieldRef`](#obj-speccomponentsquerycoordenvvaluefromfieldref)
            * [`fn withApiVersion(apiVersion)`](#fn-speccomponentsquerycoordenvvaluefromfieldrefwithapiversion)
            * [`fn withFieldPath(fieldPath)`](#fn-speccomponentsquerycoordenvvaluefromfieldrefwithfieldpath)
          * [`obj spec.components.queryCoord.env.valueFrom.resourceFieldRef`](#obj-speccomponentsquerycoordenvvaluefromresourcefieldref)
            * [`fn withContainerName(containerName)`](#fn-speccomponentsquerycoordenvvaluefromresourcefieldrefwithcontainername)
            * [`fn withDivisor(divisor)`](#fn-speccomponentsquerycoordenvvaluefromresourcefieldrefwithdivisor)
            * [`fn withResource(resource)`](#fn-speccomponentsquerycoordenvvaluefromresourcefieldrefwithresource)
          * [`obj spec.components.queryCoord.env.valueFrom.secretKeyRef`](#obj-speccomponentsquerycoordenvvaluefromsecretkeyref)
            * [`fn withKey(key)`](#fn-speccomponentsquerycoordenvvaluefromsecretkeyrefwithkey)
            * [`fn withName(name)`](#fn-speccomponentsquerycoordenvvaluefromsecretkeyrefwithname)
            * [`fn withOptional(optional)`](#fn-speccomponentsquerycoordenvvaluefromsecretkeyrefwithoptional)
      * [`obj spec.components.queryCoord.imagePullSecrets`](#obj-speccomponentsquerycoordimagepullsecrets)
        * [`fn withName(name)`](#fn-speccomponentsquerycoordimagepullsecretswithname)
      * [`obj spec.components.queryCoord.resources`](#obj-speccomponentsquerycoordresources)
        * [`fn withLimits(limits)`](#fn-speccomponentsquerycoordresourceswithlimits)
        * [`fn withLimitsMixin(limits)`](#fn-speccomponentsquerycoordresourceswithlimitsmixin)
        * [`fn withRequests(requests)`](#fn-speccomponentsquerycoordresourceswithrequests)
        * [`fn withRequestsMixin(requests)`](#fn-speccomponentsquerycoordresourceswithrequestsmixin)
      * [`obj spec.components.queryCoord.tolerations`](#obj-speccomponentsquerycoordtolerations)
        * [`fn withEffect(effect)`](#fn-speccomponentsquerycoordtolerationswitheffect)
        * [`fn withKey(key)`](#fn-speccomponentsquerycoordtolerationswithkey)
        * [`fn withOperator(operator)`](#fn-speccomponentsquerycoordtolerationswithoperator)
        * [`fn withTolerationSeconds(tolerationSeconds)`](#fn-speccomponentsquerycoordtolerationswithtolerationseconds)
        * [`fn withValue(value)`](#fn-speccomponentsquerycoordtolerationswithvalue)
      * [`obj spec.components.queryCoord.volumeMounts`](#obj-speccomponentsquerycoordvolumemounts)
        * [`fn withMountPath(mountPath)`](#fn-speccomponentsquerycoordvolumemountswithmountpath)
        * [`fn withMountPropagation(mountPropagation)`](#fn-speccomponentsquerycoordvolumemountswithmountpropagation)
        * [`fn withName(name)`](#fn-speccomponentsquerycoordvolumemountswithname)
        * [`fn withReadOnly(readOnly)`](#fn-speccomponentsquerycoordvolumemountswithreadonly)
        * [`fn withSubPath(subPath)`](#fn-speccomponentsquerycoordvolumemountswithsubpath)
        * [`fn withSubPathExpr(subPathExpr)`](#fn-speccomponentsquerycoordvolumemountswithsubpathexpr)
    * [`obj spec.components.queryNode`](#obj-speccomponentsquerynode)
      * [`fn withCommands(commands)`](#fn-speccomponentsquerynodewithcommands)
      * [`fn withCommandsMixin(commands)`](#fn-speccomponentsquerynodewithcommandsmixin)
      * [`fn withEnv(env)`](#fn-speccomponentsquerynodewithenv)
      * [`fn withEnvMixin(env)`](#fn-speccomponentsquerynodewithenvmixin)
      * [`fn withImage(image)`](#fn-speccomponentsquerynodewithimage)
      * [`fn withImagePullPolicy(imagePullPolicy)`](#fn-speccomponentsquerynodewithimagepullpolicy)
      * [`fn withImagePullSecrets(imagePullSecrets)`](#fn-speccomponentsquerynodewithimagepullsecrets)
      * [`fn withImagePullSecretsMixin(imagePullSecrets)`](#fn-speccomponentsquerynodewithimagepullsecretsmixin)
      * [`fn withInitContainers(initContainers)`](#fn-speccomponentsquerynodewithinitcontainers)
      * [`fn withInitContainersMixin(initContainers)`](#fn-speccomponentsquerynodewithinitcontainersmixin)
      * [`fn withNodeSelector(nodeSelector)`](#fn-speccomponentsquerynodewithnodeselector)
      * [`fn withNodeSelectorMixin(nodeSelector)`](#fn-speccomponentsquerynodewithnodeselectormixin)
      * [`fn withPaused(paused)`](#fn-speccomponentsquerynodewithpaused)
      * [`fn withPodAnnotations(podAnnotations)`](#fn-speccomponentsquerynodewithpodannotations)
      * [`fn withPodAnnotationsMixin(podAnnotations)`](#fn-speccomponentsquerynodewithpodannotationsmixin)
      * [`fn withPodLabels(podLabels)`](#fn-speccomponentsquerynodewithpodlabels)
      * [`fn withPodLabelsMixin(podLabels)`](#fn-speccomponentsquerynodewithpodlabelsmixin)
      * [`fn withPort(port)`](#fn-speccomponentsquerynodewithport)
      * [`fn withPriorityClassName(priorityClassName)`](#fn-speccomponentsquerynodewithpriorityclassname)
      * [`fn withReplicas(replicas)`](#fn-speccomponentsquerynodewithreplicas)
      * [`fn withRunWithSubProcess(runWithSubProcess)`](#fn-speccomponentsquerynodewithrunwithsubprocess)
      * [`fn withSchedulerName(schedulerName)`](#fn-speccomponentsquerynodewithschedulername)
      * [`fn withServiceAccountName(serviceAccountName)`](#fn-speccomponentsquerynodewithserviceaccountname)
      * [`fn withSidecars(sidecars)`](#fn-speccomponentsquerynodewithsidecars)
      * [`fn withSidecarsMixin(sidecars)`](#fn-speccomponentsquerynodewithsidecarsmixin)
      * [`fn withTolerations(tolerations)`](#fn-speccomponentsquerynodewithtolerations)
      * [`fn withTolerationsMixin(tolerations)`](#fn-speccomponentsquerynodewithtolerationsmixin)
      * [`fn withVolumeMounts(volumeMounts)`](#fn-speccomponentsquerynodewithvolumemounts)
      * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-speccomponentsquerynodewithvolumemountsmixin)
      * [`fn withVolumes(volumes)`](#fn-speccomponentsquerynodewithvolumes)
      * [`fn withVolumesMixin(volumes)`](#fn-speccomponentsquerynodewithvolumesmixin)
      * [`obj spec.components.queryNode.affinity`](#obj-speccomponentsquerynodeaffinity)
        * [`obj spec.components.queryNode.affinity.nodeAffinity`](#obj-speccomponentsquerynodeaffinitynodeaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsquerynodeaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsquerynodeaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.components.queryNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsquerynodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-speccomponentsquerynodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.components.queryNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference`](#obj-speccomponentsquerynodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreference)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsquerynodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsquerynodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressionsmixin)
              * [`fn withMatchFields(matchFields)`](#fn-speccomponentsquerynodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfields)
              * [`fn withMatchFieldsMixin(matchFields)`](#fn-speccomponentsquerynodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfieldsmixin)
              * [`obj spec.components.queryNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions`](#obj-speccomponentsquerynodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsquerynodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsquerynodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsquerynodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsquerynodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvaluesmixin)
              * [`obj spec.components.queryNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields`](#obj-speccomponentsquerynodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfields)
                * [`fn withKey(key)`](#fn-speccomponentsquerynodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsquerynodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsquerynodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsquerynodeaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvaluesmixin)
          * [`obj spec.components.queryNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsquerynodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNodeSelectorTerms(nodeSelectorTerms)`](#fn-speccomponentsquerynodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectorterms)
            * [`fn withNodeSelectorTermsMixin(nodeSelectorTerms)`](#fn-speccomponentsquerynodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectortermsmixin)
            * [`obj spec.components.queryNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms`](#obj-speccomponentsquerynodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectorterms)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsquerynodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsquerynodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressionsmixin)
              * [`fn withMatchFields(matchFields)`](#fn-speccomponentsquerynodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfields)
              * [`fn withMatchFieldsMixin(matchFields)`](#fn-speccomponentsquerynodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfieldsmixin)
              * [`obj spec.components.queryNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions`](#obj-speccomponentsquerynodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsquerynodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsquerynodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsquerynodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsquerynodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvaluesmixin)
              * [`obj spec.components.queryNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields`](#obj-speccomponentsquerynodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfields)
                * [`fn withKey(key)`](#fn-speccomponentsquerynodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsquerynodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsquerynodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsquerynodeaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvaluesmixin)
        * [`obj spec.components.queryNode.affinity.podAffinity`](#obj-speccomponentsquerynodeaffinitypodaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsquerynodeaffinitypodaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsquerynodeaffinitypodaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsquerynodeaffinitypodaffinitywithrequiredduringschedulingignoredduringexecution)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsquerynodeaffinitypodaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsquerynodeaffinitypodaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-speccomponentsquerynodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-speccomponentsquerynodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
              * [`fn withNamespaces(namespaces)`](#fn-speccomponentsquerynodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
              * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsquerynodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
              * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsquerynodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
              * [`obj spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-speccomponentsquerynodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsquerynodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsquerynodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsquerynodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsquerynodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                * [`obj spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-speccomponentsquerynodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsquerynodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsquerynodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsquerynodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsquerynodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-speccomponentsquerynodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsquerynodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsquerynodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsquerynodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsquerynodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                * [`obj spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-speccomponentsquerynodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsquerynodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsquerynodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsquerynodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsquerynodeaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
          * [`obj spec.components.queryNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsquerynodeaffinitypodaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNamespaces(namespaces)`](#fn-speccomponentsquerynodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsquerynodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsquerynodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
            * [`obj spec.components.queryNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-speccomponentsquerynodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsquerynodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsquerynodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsquerynodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsquerynodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
              * [`obj spec.components.queryNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-speccomponentsquerynodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsquerynodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsquerynodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsquerynodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsquerynodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.components.queryNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-speccomponentsquerynodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsquerynodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsquerynodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsquerynodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsquerynodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.components.queryNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-speccomponentsquerynodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsquerynodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsquerynodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsquerynodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsquerynodeaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
        * [`obj spec.components.queryNode.affinity.podAntiAffinity`](#obj-speccomponentsquerynodeaffinitypodantiaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsquerynodeaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsquerynodeaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsquerynodeaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecution)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsquerynodeaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsquerynodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-speccomponentsquerynodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-speccomponentsquerynodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
              * [`fn withNamespaces(namespaces)`](#fn-speccomponentsquerynodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
              * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsquerynodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
              * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsquerynodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
              * [`obj spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-speccomponentsquerynodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsquerynodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsquerynodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsquerynodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsquerynodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                * [`obj spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-speccomponentsquerynodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsquerynodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsquerynodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsquerynodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsquerynodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-speccomponentsquerynodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsquerynodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsquerynodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsquerynodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsquerynodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                * [`obj spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-speccomponentsquerynodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsquerynodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsquerynodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsquerynodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsquerynodeaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
          * [`obj spec.components.queryNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsquerynodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNamespaces(namespaces)`](#fn-speccomponentsquerynodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsquerynodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsquerynodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
            * [`obj spec.components.queryNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-speccomponentsquerynodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsquerynodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsquerynodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsquerynodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsquerynodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
              * [`obj spec.components.queryNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-speccomponentsquerynodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsquerynodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsquerynodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsquerynodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsquerynodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.components.queryNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-speccomponentsquerynodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsquerynodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsquerynodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsquerynodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsquerynodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.components.queryNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-speccomponentsquerynodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsquerynodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsquerynodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsquerynodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsquerynodeaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
      * [`obj spec.components.queryNode.env`](#obj-speccomponentsquerynodeenv)
        * [`fn withName(name)`](#fn-speccomponentsquerynodeenvwithname)
        * [`fn withValue(value)`](#fn-speccomponentsquerynodeenvwithvalue)
        * [`obj spec.components.queryNode.env.valueFrom`](#obj-speccomponentsquerynodeenvvaluefrom)
          * [`obj spec.components.queryNode.env.valueFrom.configMapKeyRef`](#obj-speccomponentsquerynodeenvvaluefromconfigmapkeyref)
            * [`fn withKey(key)`](#fn-speccomponentsquerynodeenvvaluefromconfigmapkeyrefwithkey)
            * [`fn withName(name)`](#fn-speccomponentsquerynodeenvvaluefromconfigmapkeyrefwithname)
            * [`fn withOptional(optional)`](#fn-speccomponentsquerynodeenvvaluefromconfigmapkeyrefwithoptional)
          * [`obj spec.components.queryNode.env.valueFrom.fieldRef`](#obj-speccomponentsquerynodeenvvaluefromfieldref)
            * [`fn withApiVersion(apiVersion)`](#fn-speccomponentsquerynodeenvvaluefromfieldrefwithapiversion)
            * [`fn withFieldPath(fieldPath)`](#fn-speccomponentsquerynodeenvvaluefromfieldrefwithfieldpath)
          * [`obj spec.components.queryNode.env.valueFrom.resourceFieldRef`](#obj-speccomponentsquerynodeenvvaluefromresourcefieldref)
            * [`fn withContainerName(containerName)`](#fn-speccomponentsquerynodeenvvaluefromresourcefieldrefwithcontainername)
            * [`fn withDivisor(divisor)`](#fn-speccomponentsquerynodeenvvaluefromresourcefieldrefwithdivisor)
            * [`fn withResource(resource)`](#fn-speccomponentsquerynodeenvvaluefromresourcefieldrefwithresource)
          * [`obj spec.components.queryNode.env.valueFrom.secretKeyRef`](#obj-speccomponentsquerynodeenvvaluefromsecretkeyref)
            * [`fn withKey(key)`](#fn-speccomponentsquerynodeenvvaluefromsecretkeyrefwithkey)
            * [`fn withName(name)`](#fn-speccomponentsquerynodeenvvaluefromsecretkeyrefwithname)
            * [`fn withOptional(optional)`](#fn-speccomponentsquerynodeenvvaluefromsecretkeyrefwithoptional)
      * [`obj spec.components.queryNode.imagePullSecrets`](#obj-speccomponentsquerynodeimagepullsecrets)
        * [`fn withName(name)`](#fn-speccomponentsquerynodeimagepullsecretswithname)
      * [`obj spec.components.queryNode.resources`](#obj-speccomponentsquerynoderesources)
        * [`fn withLimits(limits)`](#fn-speccomponentsquerynoderesourceswithlimits)
        * [`fn withLimitsMixin(limits)`](#fn-speccomponentsquerynoderesourceswithlimitsmixin)
        * [`fn withRequests(requests)`](#fn-speccomponentsquerynoderesourceswithrequests)
        * [`fn withRequestsMixin(requests)`](#fn-speccomponentsquerynoderesourceswithrequestsmixin)
      * [`obj spec.components.queryNode.tolerations`](#obj-speccomponentsquerynodetolerations)
        * [`fn withEffect(effect)`](#fn-speccomponentsquerynodetolerationswitheffect)
        * [`fn withKey(key)`](#fn-speccomponentsquerynodetolerationswithkey)
        * [`fn withOperator(operator)`](#fn-speccomponentsquerynodetolerationswithoperator)
        * [`fn withTolerationSeconds(tolerationSeconds)`](#fn-speccomponentsquerynodetolerationswithtolerationseconds)
        * [`fn withValue(value)`](#fn-speccomponentsquerynodetolerationswithvalue)
      * [`obj spec.components.queryNode.volumeMounts`](#obj-speccomponentsquerynodevolumemounts)
        * [`fn withMountPath(mountPath)`](#fn-speccomponentsquerynodevolumemountswithmountpath)
        * [`fn withMountPropagation(mountPropagation)`](#fn-speccomponentsquerynodevolumemountswithmountpropagation)
        * [`fn withName(name)`](#fn-speccomponentsquerynodevolumemountswithname)
        * [`fn withReadOnly(readOnly)`](#fn-speccomponentsquerynodevolumemountswithreadonly)
        * [`fn withSubPath(subPath)`](#fn-speccomponentsquerynodevolumemountswithsubpath)
        * [`fn withSubPathExpr(subPathExpr)`](#fn-speccomponentsquerynodevolumemountswithsubpathexpr)
    * [`obj spec.components.resources`](#obj-speccomponentsresources)
      * [`fn withLimits(limits)`](#fn-speccomponentsresourceswithlimits)
      * [`fn withLimitsMixin(limits)`](#fn-speccomponentsresourceswithlimitsmixin)
      * [`fn withRequests(requests)`](#fn-speccomponentsresourceswithrequests)
      * [`fn withRequestsMixin(requests)`](#fn-speccomponentsresourceswithrequestsmixin)
    * [`obj spec.components.rootCoord`](#obj-speccomponentsrootcoord)
      * [`fn withCommands(commands)`](#fn-speccomponentsrootcoordwithcommands)
      * [`fn withCommandsMixin(commands)`](#fn-speccomponentsrootcoordwithcommandsmixin)
      * [`fn withEnv(env)`](#fn-speccomponentsrootcoordwithenv)
      * [`fn withEnvMixin(env)`](#fn-speccomponentsrootcoordwithenvmixin)
      * [`fn withImage(image)`](#fn-speccomponentsrootcoordwithimage)
      * [`fn withImagePullPolicy(imagePullPolicy)`](#fn-speccomponentsrootcoordwithimagepullpolicy)
      * [`fn withImagePullSecrets(imagePullSecrets)`](#fn-speccomponentsrootcoordwithimagepullsecrets)
      * [`fn withImagePullSecretsMixin(imagePullSecrets)`](#fn-speccomponentsrootcoordwithimagepullsecretsmixin)
      * [`fn withInitContainers(initContainers)`](#fn-speccomponentsrootcoordwithinitcontainers)
      * [`fn withInitContainersMixin(initContainers)`](#fn-speccomponentsrootcoordwithinitcontainersmixin)
      * [`fn withNodeSelector(nodeSelector)`](#fn-speccomponentsrootcoordwithnodeselector)
      * [`fn withNodeSelectorMixin(nodeSelector)`](#fn-speccomponentsrootcoordwithnodeselectormixin)
      * [`fn withPaused(paused)`](#fn-speccomponentsrootcoordwithpaused)
      * [`fn withPodAnnotations(podAnnotations)`](#fn-speccomponentsrootcoordwithpodannotations)
      * [`fn withPodAnnotationsMixin(podAnnotations)`](#fn-speccomponentsrootcoordwithpodannotationsmixin)
      * [`fn withPodLabels(podLabels)`](#fn-speccomponentsrootcoordwithpodlabels)
      * [`fn withPodLabelsMixin(podLabels)`](#fn-speccomponentsrootcoordwithpodlabelsmixin)
      * [`fn withPort(port)`](#fn-speccomponentsrootcoordwithport)
      * [`fn withPriorityClassName(priorityClassName)`](#fn-speccomponentsrootcoordwithpriorityclassname)
      * [`fn withReplicas(replicas)`](#fn-speccomponentsrootcoordwithreplicas)
      * [`fn withRunWithSubProcess(runWithSubProcess)`](#fn-speccomponentsrootcoordwithrunwithsubprocess)
      * [`fn withSchedulerName(schedulerName)`](#fn-speccomponentsrootcoordwithschedulername)
      * [`fn withServiceAccountName(serviceAccountName)`](#fn-speccomponentsrootcoordwithserviceaccountname)
      * [`fn withSidecars(sidecars)`](#fn-speccomponentsrootcoordwithsidecars)
      * [`fn withSidecarsMixin(sidecars)`](#fn-speccomponentsrootcoordwithsidecarsmixin)
      * [`fn withTolerations(tolerations)`](#fn-speccomponentsrootcoordwithtolerations)
      * [`fn withTolerationsMixin(tolerations)`](#fn-speccomponentsrootcoordwithtolerationsmixin)
      * [`fn withVolumeMounts(volumeMounts)`](#fn-speccomponentsrootcoordwithvolumemounts)
      * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-speccomponentsrootcoordwithvolumemountsmixin)
      * [`fn withVolumes(volumes)`](#fn-speccomponentsrootcoordwithvolumes)
      * [`fn withVolumesMixin(volumes)`](#fn-speccomponentsrootcoordwithvolumesmixin)
      * [`obj spec.components.rootCoord.affinity`](#obj-speccomponentsrootcoordaffinity)
        * [`obj spec.components.rootCoord.affinity.nodeAffinity`](#obj-speccomponentsrootcoordaffinitynodeaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsrootcoordaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsrootcoordaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.components.rootCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsrootcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-speccomponentsrootcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.components.rootCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference`](#obj-speccomponentsrootcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreference)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsrootcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsrootcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressionsmixin)
              * [`fn withMatchFields(matchFields)`](#fn-speccomponentsrootcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfields)
              * [`fn withMatchFieldsMixin(matchFields)`](#fn-speccomponentsrootcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfieldsmixin)
              * [`obj spec.components.rootCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions`](#obj-speccomponentsrootcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsrootcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsrootcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsrootcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsrootcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvaluesmixin)
              * [`obj spec.components.rootCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields`](#obj-speccomponentsrootcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfields)
                * [`fn withKey(key)`](#fn-speccomponentsrootcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsrootcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsrootcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsrootcoordaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvaluesmixin)
          * [`obj spec.components.rootCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsrootcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNodeSelectorTerms(nodeSelectorTerms)`](#fn-speccomponentsrootcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectorterms)
            * [`fn withNodeSelectorTermsMixin(nodeSelectorTerms)`](#fn-speccomponentsrootcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectortermsmixin)
            * [`obj spec.components.rootCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms`](#obj-speccomponentsrootcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectorterms)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsrootcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsrootcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressionsmixin)
              * [`fn withMatchFields(matchFields)`](#fn-speccomponentsrootcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfields)
              * [`fn withMatchFieldsMixin(matchFields)`](#fn-speccomponentsrootcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfieldsmixin)
              * [`obj spec.components.rootCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions`](#obj-speccomponentsrootcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsrootcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsrootcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsrootcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsrootcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvaluesmixin)
              * [`obj spec.components.rootCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields`](#obj-speccomponentsrootcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfields)
                * [`fn withKey(key)`](#fn-speccomponentsrootcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsrootcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsrootcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsrootcoordaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvaluesmixin)
        * [`obj spec.components.rootCoord.affinity.podAffinity`](#obj-speccomponentsrootcoordaffinitypodaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsrootcoordaffinitypodaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsrootcoordaffinitypodaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsrootcoordaffinitypodaffinitywithrequiredduringschedulingignoredduringexecution)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsrootcoordaffinitypodaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsrootcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-speccomponentsrootcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-speccomponentsrootcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
              * [`fn withNamespaces(namespaces)`](#fn-speccomponentsrootcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
              * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsrootcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
              * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsrootcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
              * [`obj spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-speccomponentsrootcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsrootcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsrootcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsrootcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsrootcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                * [`obj spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-speccomponentsrootcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsrootcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsrootcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsrootcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsrootcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-speccomponentsrootcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsrootcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsrootcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsrootcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsrootcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                * [`obj spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-speccomponentsrootcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsrootcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsrootcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsrootcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsrootcoordaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
          * [`obj spec.components.rootCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsrootcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNamespaces(namespaces)`](#fn-speccomponentsrootcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsrootcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsrootcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
            * [`obj spec.components.rootCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-speccomponentsrootcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsrootcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsrootcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsrootcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsrootcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
              * [`obj spec.components.rootCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-speccomponentsrootcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsrootcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsrootcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsrootcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsrootcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.components.rootCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-speccomponentsrootcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsrootcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsrootcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsrootcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsrootcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.components.rootCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-speccomponentsrootcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsrootcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsrootcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsrootcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsrootcoordaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
        * [`obj spec.components.rootCoord.affinity.podAntiAffinity`](#obj-speccomponentsrootcoordaffinitypodantiaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsrootcoordaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsrootcoordaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsrootcoordaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecution)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsrootcoordaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsrootcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-speccomponentsrootcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-speccomponentsrootcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
              * [`fn withNamespaces(namespaces)`](#fn-speccomponentsrootcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
              * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsrootcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
              * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsrootcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
              * [`obj spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-speccomponentsrootcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsrootcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsrootcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsrootcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsrootcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                * [`obj spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-speccomponentsrootcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsrootcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsrootcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsrootcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsrootcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-speccomponentsrootcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsrootcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsrootcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsrootcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsrootcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                * [`obj spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-speccomponentsrootcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsrootcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsrootcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsrootcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsrootcoordaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
          * [`obj spec.components.rootCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsrootcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNamespaces(namespaces)`](#fn-speccomponentsrootcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsrootcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsrootcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
            * [`obj spec.components.rootCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-speccomponentsrootcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsrootcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsrootcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsrootcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsrootcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
              * [`obj spec.components.rootCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-speccomponentsrootcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsrootcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsrootcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsrootcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsrootcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.components.rootCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-speccomponentsrootcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsrootcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsrootcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsrootcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsrootcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.components.rootCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-speccomponentsrootcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsrootcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsrootcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsrootcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsrootcoordaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
      * [`obj spec.components.rootCoord.env`](#obj-speccomponentsrootcoordenv)
        * [`fn withName(name)`](#fn-speccomponentsrootcoordenvwithname)
        * [`fn withValue(value)`](#fn-speccomponentsrootcoordenvwithvalue)
        * [`obj spec.components.rootCoord.env.valueFrom`](#obj-speccomponentsrootcoordenvvaluefrom)
          * [`obj spec.components.rootCoord.env.valueFrom.configMapKeyRef`](#obj-speccomponentsrootcoordenvvaluefromconfigmapkeyref)
            * [`fn withKey(key)`](#fn-speccomponentsrootcoordenvvaluefromconfigmapkeyrefwithkey)
            * [`fn withName(name)`](#fn-speccomponentsrootcoordenvvaluefromconfigmapkeyrefwithname)
            * [`fn withOptional(optional)`](#fn-speccomponentsrootcoordenvvaluefromconfigmapkeyrefwithoptional)
          * [`obj spec.components.rootCoord.env.valueFrom.fieldRef`](#obj-speccomponentsrootcoordenvvaluefromfieldref)
            * [`fn withApiVersion(apiVersion)`](#fn-speccomponentsrootcoordenvvaluefromfieldrefwithapiversion)
            * [`fn withFieldPath(fieldPath)`](#fn-speccomponentsrootcoordenvvaluefromfieldrefwithfieldpath)
          * [`obj spec.components.rootCoord.env.valueFrom.resourceFieldRef`](#obj-speccomponentsrootcoordenvvaluefromresourcefieldref)
            * [`fn withContainerName(containerName)`](#fn-speccomponentsrootcoordenvvaluefromresourcefieldrefwithcontainername)
            * [`fn withDivisor(divisor)`](#fn-speccomponentsrootcoordenvvaluefromresourcefieldrefwithdivisor)
            * [`fn withResource(resource)`](#fn-speccomponentsrootcoordenvvaluefromresourcefieldrefwithresource)
          * [`obj spec.components.rootCoord.env.valueFrom.secretKeyRef`](#obj-speccomponentsrootcoordenvvaluefromsecretkeyref)
            * [`fn withKey(key)`](#fn-speccomponentsrootcoordenvvaluefromsecretkeyrefwithkey)
            * [`fn withName(name)`](#fn-speccomponentsrootcoordenvvaluefromsecretkeyrefwithname)
            * [`fn withOptional(optional)`](#fn-speccomponentsrootcoordenvvaluefromsecretkeyrefwithoptional)
      * [`obj spec.components.rootCoord.imagePullSecrets`](#obj-speccomponentsrootcoordimagepullsecrets)
        * [`fn withName(name)`](#fn-speccomponentsrootcoordimagepullsecretswithname)
      * [`obj spec.components.rootCoord.resources`](#obj-speccomponentsrootcoordresources)
        * [`fn withLimits(limits)`](#fn-speccomponentsrootcoordresourceswithlimits)
        * [`fn withLimitsMixin(limits)`](#fn-speccomponentsrootcoordresourceswithlimitsmixin)
        * [`fn withRequests(requests)`](#fn-speccomponentsrootcoordresourceswithrequests)
        * [`fn withRequestsMixin(requests)`](#fn-speccomponentsrootcoordresourceswithrequestsmixin)
      * [`obj spec.components.rootCoord.tolerations`](#obj-speccomponentsrootcoordtolerations)
        * [`fn withEffect(effect)`](#fn-speccomponentsrootcoordtolerationswitheffect)
        * [`fn withKey(key)`](#fn-speccomponentsrootcoordtolerationswithkey)
        * [`fn withOperator(operator)`](#fn-speccomponentsrootcoordtolerationswithoperator)
        * [`fn withTolerationSeconds(tolerationSeconds)`](#fn-speccomponentsrootcoordtolerationswithtolerationseconds)
        * [`fn withValue(value)`](#fn-speccomponentsrootcoordtolerationswithvalue)
      * [`obj spec.components.rootCoord.volumeMounts`](#obj-speccomponentsrootcoordvolumemounts)
        * [`fn withMountPath(mountPath)`](#fn-speccomponentsrootcoordvolumemountswithmountpath)
        * [`fn withMountPropagation(mountPropagation)`](#fn-speccomponentsrootcoordvolumemountswithmountpropagation)
        * [`fn withName(name)`](#fn-speccomponentsrootcoordvolumemountswithname)
        * [`fn withReadOnly(readOnly)`](#fn-speccomponentsrootcoordvolumemountswithreadonly)
        * [`fn withSubPath(subPath)`](#fn-speccomponentsrootcoordvolumemountswithsubpath)
        * [`fn withSubPathExpr(subPathExpr)`](#fn-speccomponentsrootcoordvolumemountswithsubpathexpr)
    * [`obj spec.components.standalone`](#obj-speccomponentsstandalone)
      * [`fn withCommands(commands)`](#fn-speccomponentsstandalonewithcommands)
      * [`fn withCommandsMixin(commands)`](#fn-speccomponentsstandalonewithcommandsmixin)
      * [`fn withEnv(env)`](#fn-speccomponentsstandalonewithenv)
      * [`fn withEnvMixin(env)`](#fn-speccomponentsstandalonewithenvmixin)
      * [`fn withImage(image)`](#fn-speccomponentsstandalonewithimage)
      * [`fn withImagePullPolicy(imagePullPolicy)`](#fn-speccomponentsstandalonewithimagepullpolicy)
      * [`fn withImagePullSecrets(imagePullSecrets)`](#fn-speccomponentsstandalonewithimagepullsecrets)
      * [`fn withImagePullSecretsMixin(imagePullSecrets)`](#fn-speccomponentsstandalonewithimagepullsecretsmixin)
      * [`fn withInitContainers(initContainers)`](#fn-speccomponentsstandalonewithinitcontainers)
      * [`fn withInitContainersMixin(initContainers)`](#fn-speccomponentsstandalonewithinitcontainersmixin)
      * [`fn withNodeSelector(nodeSelector)`](#fn-speccomponentsstandalonewithnodeselector)
      * [`fn withNodeSelectorMixin(nodeSelector)`](#fn-speccomponentsstandalonewithnodeselectormixin)
      * [`fn withPaused(paused)`](#fn-speccomponentsstandalonewithpaused)
      * [`fn withPodAnnotations(podAnnotations)`](#fn-speccomponentsstandalonewithpodannotations)
      * [`fn withPodAnnotationsMixin(podAnnotations)`](#fn-speccomponentsstandalonewithpodannotationsmixin)
      * [`fn withPodLabels(podLabels)`](#fn-speccomponentsstandalonewithpodlabels)
      * [`fn withPodLabelsMixin(podLabels)`](#fn-speccomponentsstandalonewithpodlabelsmixin)
      * [`fn withPort(port)`](#fn-speccomponentsstandalonewithport)
      * [`fn withPriorityClassName(priorityClassName)`](#fn-speccomponentsstandalonewithpriorityclassname)
      * [`fn withReplicas(replicas)`](#fn-speccomponentsstandalonewithreplicas)
      * [`fn withRunWithSubProcess(runWithSubProcess)`](#fn-speccomponentsstandalonewithrunwithsubprocess)
      * [`fn withSchedulerName(schedulerName)`](#fn-speccomponentsstandalonewithschedulername)
      * [`fn withServiceAccountName(serviceAccountName)`](#fn-speccomponentsstandalonewithserviceaccountname)
      * [`fn withServiceAnnotations(serviceAnnotations)`](#fn-speccomponentsstandalonewithserviceannotations)
      * [`fn withServiceAnnotationsMixin(serviceAnnotations)`](#fn-speccomponentsstandalonewithserviceannotationsmixin)
      * [`fn withServiceLabels(serviceLabels)`](#fn-speccomponentsstandalonewithservicelabels)
      * [`fn withServiceLabelsMixin(serviceLabels)`](#fn-speccomponentsstandalonewithservicelabelsmixin)
      * [`fn withServiceRestfulPort(serviceRestfulPort)`](#fn-speccomponentsstandalonewithservicerestfulport)
      * [`fn withServiceType(serviceType)`](#fn-speccomponentsstandalonewithservicetype)
      * [`fn withSidecars(sidecars)`](#fn-speccomponentsstandalonewithsidecars)
      * [`fn withSidecarsMixin(sidecars)`](#fn-speccomponentsstandalonewithsidecarsmixin)
      * [`fn withTolerations(tolerations)`](#fn-speccomponentsstandalonewithtolerations)
      * [`fn withTolerationsMixin(tolerations)`](#fn-speccomponentsstandalonewithtolerationsmixin)
      * [`fn withVolumeMounts(volumeMounts)`](#fn-speccomponentsstandalonewithvolumemounts)
      * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-speccomponentsstandalonewithvolumemountsmixin)
      * [`fn withVolumes(volumes)`](#fn-speccomponentsstandalonewithvolumes)
      * [`fn withVolumesMixin(volumes)`](#fn-speccomponentsstandalonewithvolumesmixin)
      * [`obj spec.components.standalone.affinity`](#obj-speccomponentsstandaloneaffinity)
        * [`obj spec.components.standalone.affinity.nodeAffinity`](#obj-speccomponentsstandaloneaffinitynodeaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsstandaloneaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsstandaloneaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.components.standalone.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsstandaloneaffinitynodeaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-speccomponentsstandaloneaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.components.standalone.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference`](#obj-speccomponentsstandaloneaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreference)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsstandaloneaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsstandaloneaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressionsmixin)
              * [`fn withMatchFields(matchFields)`](#fn-speccomponentsstandaloneaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfields)
              * [`fn withMatchFieldsMixin(matchFields)`](#fn-speccomponentsstandaloneaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfieldsmixin)
              * [`obj spec.components.standalone.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions`](#obj-speccomponentsstandaloneaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsstandaloneaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsstandaloneaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsstandaloneaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsstandaloneaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvaluesmixin)
              * [`obj spec.components.standalone.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields`](#obj-speccomponentsstandaloneaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfields)
                * [`fn withKey(key)`](#fn-speccomponentsstandaloneaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsstandaloneaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsstandaloneaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsstandaloneaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvaluesmixin)
          * [`obj spec.components.standalone.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsstandaloneaffinitynodeaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNodeSelectorTerms(nodeSelectorTerms)`](#fn-speccomponentsstandaloneaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectorterms)
            * [`fn withNodeSelectorTermsMixin(nodeSelectorTerms)`](#fn-speccomponentsstandaloneaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectortermsmixin)
            * [`obj spec.components.standalone.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms`](#obj-speccomponentsstandaloneaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectorterms)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsstandaloneaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsstandaloneaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressionsmixin)
              * [`fn withMatchFields(matchFields)`](#fn-speccomponentsstandaloneaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfields)
              * [`fn withMatchFieldsMixin(matchFields)`](#fn-speccomponentsstandaloneaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfieldsmixin)
              * [`obj spec.components.standalone.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions`](#obj-speccomponentsstandaloneaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsstandaloneaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsstandaloneaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsstandaloneaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsstandaloneaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvaluesmixin)
              * [`obj spec.components.standalone.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields`](#obj-speccomponentsstandaloneaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfields)
                * [`fn withKey(key)`](#fn-speccomponentsstandaloneaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsstandaloneaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsstandaloneaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsstandaloneaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvaluesmixin)
        * [`obj spec.components.standalone.affinity.podAffinity`](#obj-speccomponentsstandaloneaffinitypodaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsstandaloneaffinitypodaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsstandaloneaffinitypodaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsstandaloneaffinitypodaffinitywithrequiredduringschedulingignoredduringexecution)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsstandaloneaffinitypodaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsstandaloneaffinitypodaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-speccomponentsstandaloneaffinitypodaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-speccomponentsstandaloneaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
              * [`fn withNamespaces(namespaces)`](#fn-speccomponentsstandaloneaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
              * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsstandaloneaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
              * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsstandaloneaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
              * [`obj spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-speccomponentsstandaloneaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsstandaloneaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsstandaloneaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsstandaloneaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsstandaloneaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                * [`obj spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-speccomponentsstandaloneaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsstandaloneaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsstandaloneaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsstandaloneaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsstandaloneaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-speccomponentsstandaloneaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsstandaloneaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsstandaloneaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsstandaloneaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsstandaloneaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                * [`obj spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-speccomponentsstandaloneaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsstandaloneaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsstandaloneaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsstandaloneaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsstandaloneaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
          * [`obj spec.components.standalone.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsstandaloneaffinitypodaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNamespaces(namespaces)`](#fn-speccomponentsstandaloneaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsstandaloneaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsstandaloneaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
            * [`obj spec.components.standalone.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-speccomponentsstandaloneaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsstandaloneaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsstandaloneaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsstandaloneaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsstandaloneaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
              * [`obj spec.components.standalone.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-speccomponentsstandaloneaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsstandaloneaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsstandaloneaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsstandaloneaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsstandaloneaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.components.standalone.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-speccomponentsstandaloneaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsstandaloneaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsstandaloneaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsstandaloneaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsstandaloneaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.components.standalone.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-speccomponentsstandaloneaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsstandaloneaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsstandaloneaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsstandaloneaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsstandaloneaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
        * [`obj spec.components.standalone.affinity.podAntiAffinity`](#obj-speccomponentsstandaloneaffinitypodantiaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsstandaloneaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsstandaloneaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsstandaloneaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecution)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speccomponentsstandaloneaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsstandaloneaffinitypodantiaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-speccomponentsstandaloneaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-speccomponentsstandaloneaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
              * [`fn withNamespaces(namespaces)`](#fn-speccomponentsstandaloneaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
              * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsstandaloneaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
              * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsstandaloneaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
              * [`obj spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-speccomponentsstandaloneaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsstandaloneaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsstandaloneaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsstandaloneaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsstandaloneaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                * [`obj spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-speccomponentsstandaloneaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsstandaloneaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsstandaloneaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsstandaloneaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsstandaloneaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-speccomponentsstandaloneaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsstandaloneaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsstandaloneaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsstandaloneaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsstandaloneaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                * [`obj spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-speccomponentsstandaloneaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-speccomponentsstandaloneaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-speccomponentsstandaloneaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-speccomponentsstandaloneaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-speccomponentsstandaloneaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
          * [`obj spec.components.standalone.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speccomponentsstandaloneaffinitypodantiaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNamespaces(namespaces)`](#fn-speccomponentsstandaloneaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-speccomponentsstandaloneaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-speccomponentsstandaloneaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
            * [`obj spec.components.standalone.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-speccomponentsstandaloneaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsstandaloneaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsstandaloneaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsstandaloneaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsstandaloneaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
              * [`obj spec.components.standalone.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-speccomponentsstandaloneaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsstandaloneaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsstandaloneaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsstandaloneaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsstandaloneaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.components.standalone.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-speccomponentsstandaloneaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccomponentsstandaloneaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccomponentsstandaloneaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccomponentsstandaloneaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccomponentsstandaloneaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.components.standalone.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-speccomponentsstandaloneaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccomponentsstandaloneaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccomponentsstandaloneaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccomponentsstandaloneaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccomponentsstandaloneaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
      * [`obj spec.components.standalone.env`](#obj-speccomponentsstandaloneenv)
        * [`fn withName(name)`](#fn-speccomponentsstandaloneenvwithname)
        * [`fn withValue(value)`](#fn-speccomponentsstandaloneenvwithvalue)
        * [`obj spec.components.standalone.env.valueFrom`](#obj-speccomponentsstandaloneenvvaluefrom)
          * [`obj spec.components.standalone.env.valueFrom.configMapKeyRef`](#obj-speccomponentsstandaloneenvvaluefromconfigmapkeyref)
            * [`fn withKey(key)`](#fn-speccomponentsstandaloneenvvaluefromconfigmapkeyrefwithkey)
            * [`fn withName(name)`](#fn-speccomponentsstandaloneenvvaluefromconfigmapkeyrefwithname)
            * [`fn withOptional(optional)`](#fn-speccomponentsstandaloneenvvaluefromconfigmapkeyrefwithoptional)
          * [`obj spec.components.standalone.env.valueFrom.fieldRef`](#obj-speccomponentsstandaloneenvvaluefromfieldref)
            * [`fn withApiVersion(apiVersion)`](#fn-speccomponentsstandaloneenvvaluefromfieldrefwithapiversion)
            * [`fn withFieldPath(fieldPath)`](#fn-speccomponentsstandaloneenvvaluefromfieldrefwithfieldpath)
          * [`obj spec.components.standalone.env.valueFrom.resourceFieldRef`](#obj-speccomponentsstandaloneenvvaluefromresourcefieldref)
            * [`fn withContainerName(containerName)`](#fn-speccomponentsstandaloneenvvaluefromresourcefieldrefwithcontainername)
            * [`fn withDivisor(divisor)`](#fn-speccomponentsstandaloneenvvaluefromresourcefieldrefwithdivisor)
            * [`fn withResource(resource)`](#fn-speccomponentsstandaloneenvvaluefromresourcefieldrefwithresource)
          * [`obj spec.components.standalone.env.valueFrom.secretKeyRef`](#obj-speccomponentsstandaloneenvvaluefromsecretkeyref)
            * [`fn withKey(key)`](#fn-speccomponentsstandaloneenvvaluefromsecretkeyrefwithkey)
            * [`fn withName(name)`](#fn-speccomponentsstandaloneenvvaluefromsecretkeyrefwithname)
            * [`fn withOptional(optional)`](#fn-speccomponentsstandaloneenvvaluefromsecretkeyrefwithoptional)
      * [`obj spec.components.standalone.imagePullSecrets`](#obj-speccomponentsstandaloneimagepullsecrets)
        * [`fn withName(name)`](#fn-speccomponentsstandaloneimagepullsecretswithname)
      * [`obj spec.components.standalone.ingress`](#obj-speccomponentsstandaloneingress)
        * [`fn withAnnotations(annotations)`](#fn-speccomponentsstandaloneingresswithannotations)
        * [`fn withAnnotationsMixin(annotations)`](#fn-speccomponentsstandaloneingresswithannotationsmixin)
        * [`fn withHosts(hosts)`](#fn-speccomponentsstandaloneingresswithhosts)
        * [`fn withHostsMixin(hosts)`](#fn-speccomponentsstandaloneingresswithhostsmixin)
        * [`fn withIngressClassName(ingressClassName)`](#fn-speccomponentsstandaloneingresswithingressclassname)
        * [`fn withLabels(labels)`](#fn-speccomponentsstandaloneingresswithlabels)
        * [`fn withLabelsMixin(labels)`](#fn-speccomponentsstandaloneingresswithlabelsmixin)
        * [`fn withTlsSecretRefs(tlsSecretRefs)`](#fn-speccomponentsstandaloneingresswithtlssecretrefs)
        * [`fn withTlsSecretRefsMixin(tlsSecretRefs)`](#fn-speccomponentsstandaloneingresswithtlssecretrefsmixin)
      * [`obj spec.components.standalone.resources`](#obj-speccomponentsstandaloneresources)
        * [`fn withLimits(limits)`](#fn-speccomponentsstandaloneresourceswithlimits)
        * [`fn withLimitsMixin(limits)`](#fn-speccomponentsstandaloneresourceswithlimitsmixin)
        * [`fn withRequests(requests)`](#fn-speccomponentsstandaloneresourceswithrequests)
        * [`fn withRequestsMixin(requests)`](#fn-speccomponentsstandaloneresourceswithrequestsmixin)
      * [`obj spec.components.standalone.tolerations`](#obj-speccomponentsstandalonetolerations)
        * [`fn withEffect(effect)`](#fn-speccomponentsstandalonetolerationswitheffect)
        * [`fn withKey(key)`](#fn-speccomponentsstandalonetolerationswithkey)
        * [`fn withOperator(operator)`](#fn-speccomponentsstandalonetolerationswithoperator)
        * [`fn withTolerationSeconds(tolerationSeconds)`](#fn-speccomponentsstandalonetolerationswithtolerationseconds)
        * [`fn withValue(value)`](#fn-speccomponentsstandalonetolerationswithvalue)
      * [`obj spec.components.standalone.volumeMounts`](#obj-speccomponentsstandalonevolumemounts)
        * [`fn withMountPath(mountPath)`](#fn-speccomponentsstandalonevolumemountswithmountpath)
        * [`fn withMountPropagation(mountPropagation)`](#fn-speccomponentsstandalonevolumemountswithmountpropagation)
        * [`fn withName(name)`](#fn-speccomponentsstandalonevolumemountswithname)
        * [`fn withReadOnly(readOnly)`](#fn-speccomponentsstandalonevolumemountswithreadonly)
        * [`fn withSubPath(subPath)`](#fn-speccomponentsstandalonevolumemountswithsubpath)
        * [`fn withSubPathExpr(subPathExpr)`](#fn-speccomponentsstandalonevolumemountswithsubpathexpr)
    * [`obj spec.components.tolerations`](#obj-speccomponentstolerations)
      * [`fn withEffect(effect)`](#fn-speccomponentstolerationswitheffect)
      * [`fn withKey(key)`](#fn-speccomponentstolerationswithkey)
      * [`fn withOperator(operator)`](#fn-speccomponentstolerationswithoperator)
      * [`fn withTolerationSeconds(tolerationSeconds)`](#fn-speccomponentstolerationswithtolerationseconds)
      * [`fn withValue(value)`](#fn-speccomponentstolerationswithvalue)
    * [`obj spec.components.volumeMounts`](#obj-speccomponentsvolumemounts)
      * [`fn withMountPath(mountPath)`](#fn-speccomponentsvolumemountswithmountpath)
      * [`fn withMountPropagation(mountPropagation)`](#fn-speccomponentsvolumemountswithmountpropagation)
      * [`fn withName(name)`](#fn-speccomponentsvolumemountswithname)
      * [`fn withReadOnly(readOnly)`](#fn-speccomponentsvolumemountswithreadonly)
      * [`fn withSubPath(subPath)`](#fn-speccomponentsvolumemountswithsubpath)
      * [`fn withSubPathExpr(subPathExpr)`](#fn-speccomponentsvolumemountswithsubpathexpr)
  * [`obj spec.dependencies`](#obj-specdependencies)
    * [`fn withCustomMsgStream(customMsgStream)`](#fn-specdependencieswithcustommsgstream)
    * [`fn withCustomMsgStreamMixin(customMsgStream)`](#fn-specdependencieswithcustommsgstreammixin)
    * [`fn withMsgStreamType(msgStreamType)`](#fn-specdependencieswithmsgstreamtype)
    * [`obj spec.dependencies.etcd`](#obj-specdependenciesetcd)
      * [`fn withEndpoints(endpoints)`](#fn-specdependenciesetcdwithendpoints)
      * [`fn withEndpointsMixin(endpoints)`](#fn-specdependenciesetcdwithendpointsmixin)
      * [`fn withExternal(external)`](#fn-specdependenciesetcdwithexternal)
      * [`obj spec.dependencies.etcd.inCluster`](#obj-specdependenciesetcdincluster)
        * [`fn withDeletionPolicy(deletionPolicy)`](#fn-specdependenciesetcdinclusterwithdeletionpolicy)
        * [`fn withPvcDeletion(pvcDeletion)`](#fn-specdependenciesetcdinclusterwithpvcdeletion)
        * [`fn withValues(values)`](#fn-specdependenciesetcdinclusterwithvalues)
        * [`fn withValuesMixin(values)`](#fn-specdependenciesetcdinclusterwithvaluesmixin)
    * [`obj spec.dependencies.kafka`](#obj-specdependencieskafka)
      * [`fn withBrokerList(brokerList)`](#fn-specdependencieskafkawithbrokerlist)
      * [`fn withBrokerListMixin(brokerList)`](#fn-specdependencieskafkawithbrokerlistmixin)
      * [`fn withExternal(external)`](#fn-specdependencieskafkawithexternal)
      * [`obj spec.dependencies.kafka.inCluster`](#obj-specdependencieskafkaincluster)
        * [`fn withDeletionPolicy(deletionPolicy)`](#fn-specdependencieskafkainclusterwithdeletionpolicy)
        * [`fn withPvcDeletion(pvcDeletion)`](#fn-specdependencieskafkainclusterwithpvcdeletion)
        * [`fn withValues(values)`](#fn-specdependencieskafkainclusterwithvalues)
        * [`fn withValuesMixin(values)`](#fn-specdependencieskafkainclusterwithvaluesmixin)
    * [`obj spec.dependencies.natsmq`](#obj-specdependenciesnatsmq)
      * [`obj spec.dependencies.natsmq.persistence`](#obj-specdependenciesnatsmqpersistence)
        * [`fn withEnabled(enabled)`](#fn-specdependenciesnatsmqpersistencewithenabled)
        * [`fn withPvcDeletion(pvcDeletion)`](#fn-specdependenciesnatsmqpersistencewithpvcdeletion)
        * [`obj spec.dependencies.natsmq.persistence.persistentVolumeClaim`](#obj-specdependenciesnatsmqpersistencepersistentvolumeclaim)
          * [`fn withAnnotations(annotations)`](#fn-specdependenciesnatsmqpersistencepersistentvolumeclaimwithannotations)
          * [`fn withAnnotationsMixin(annotations)`](#fn-specdependenciesnatsmqpersistencepersistentvolumeclaimwithannotationsmixin)
          * [`fn withExistingClaim(existingClaim)`](#fn-specdependenciesnatsmqpersistencepersistentvolumeclaimwithexistingclaim)
          * [`fn withLabels(labels)`](#fn-specdependenciesnatsmqpersistencepersistentvolumeclaimwithlabels)
          * [`fn withLabelsMixin(labels)`](#fn-specdependenciesnatsmqpersistencepersistentvolumeclaimwithlabelsmixin)
          * [`fn withSpec(spec)`](#fn-specdependenciesnatsmqpersistencepersistentvolumeclaimwithspec)
          * [`fn withSpecMixin(spec)`](#fn-specdependenciesnatsmqpersistencepersistentvolumeclaimwithspecmixin)
    * [`obj spec.dependencies.pulsar`](#obj-specdependenciespulsar)
      * [`fn withEndpoint(endpoint)`](#fn-specdependenciespulsarwithendpoint)
      * [`fn withExternal(external)`](#fn-specdependenciespulsarwithexternal)
      * [`obj spec.dependencies.pulsar.inCluster`](#obj-specdependenciespulsarincluster)
        * [`fn withDeletionPolicy(deletionPolicy)`](#fn-specdependenciespulsarinclusterwithdeletionpolicy)
        * [`fn withPvcDeletion(pvcDeletion)`](#fn-specdependenciespulsarinclusterwithpvcdeletion)
        * [`fn withValues(values)`](#fn-specdependenciespulsarinclusterwithvalues)
        * [`fn withValuesMixin(values)`](#fn-specdependenciespulsarinclusterwithvaluesmixin)
    * [`obj spec.dependencies.rocksmq`](#obj-specdependenciesrocksmq)
      * [`obj spec.dependencies.rocksmq.persistence`](#obj-specdependenciesrocksmqpersistence)
        * [`fn withEnabled(enabled)`](#fn-specdependenciesrocksmqpersistencewithenabled)
        * [`fn withPvcDeletion(pvcDeletion)`](#fn-specdependenciesrocksmqpersistencewithpvcdeletion)
        * [`obj spec.dependencies.rocksmq.persistence.persistentVolumeClaim`](#obj-specdependenciesrocksmqpersistencepersistentvolumeclaim)
          * [`fn withAnnotations(annotations)`](#fn-specdependenciesrocksmqpersistencepersistentvolumeclaimwithannotations)
          * [`fn withAnnotationsMixin(annotations)`](#fn-specdependenciesrocksmqpersistencepersistentvolumeclaimwithannotationsmixin)
          * [`fn withExistingClaim(existingClaim)`](#fn-specdependenciesrocksmqpersistencepersistentvolumeclaimwithexistingclaim)
          * [`fn withLabels(labels)`](#fn-specdependenciesrocksmqpersistencepersistentvolumeclaimwithlabels)
          * [`fn withLabelsMixin(labels)`](#fn-specdependenciesrocksmqpersistencepersistentvolumeclaimwithlabelsmixin)
          * [`fn withSpec(spec)`](#fn-specdependenciesrocksmqpersistencepersistentvolumeclaimwithspec)
          * [`fn withSpecMixin(spec)`](#fn-specdependenciesrocksmqpersistencepersistentvolumeclaimwithspecmixin)
    * [`obj spec.dependencies.storage`](#obj-specdependenciesstorage)
      * [`fn withEndpoint(endpoint)`](#fn-specdependenciesstoragewithendpoint)
      * [`fn withExternal(external)`](#fn-specdependenciesstoragewithexternal)
      * [`fn withSecretRef(secretRef)`](#fn-specdependenciesstoragewithsecretref)
      * [`fn withType(type)`](#fn-specdependenciesstoragewithtype)
      * [`obj spec.dependencies.storage.inCluster`](#obj-specdependenciesstorageincluster)
        * [`fn withDeletionPolicy(deletionPolicy)`](#fn-specdependenciesstorageinclusterwithdeletionpolicy)
        * [`fn withPvcDeletion(pvcDeletion)`](#fn-specdependenciesstorageinclusterwithpvcdeletion)
        * [`fn withValues(values)`](#fn-specdependenciesstorageinclusterwithvalues)
        * [`fn withValuesMixin(values)`](#fn-specdependenciesstorageinclusterwithvaluesmixin)

## Fields

### fn new

```ts
new(name)
```

new returns an instance of MilvusCluster

## obj metadata

"ObjectMeta is metadata that all persisted resources must have, which includes all objects users must create."

### fn metadata.withAnnotations

```ts
withAnnotations(annotations)
```

"Annotations is an unstructured key value map stored with a resource that may be set by external tools to store and retrieve arbitrary metadata. They are not queryable and should be preserved when modifying objects. More info: http://kubernetes.io/docs/user-guide/annotations"

### fn metadata.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```

"Annotations is an unstructured key value map stored with a resource that may be set by external tools to store and retrieve arbitrary metadata. They are not queryable and should be preserved when modifying objects. More info: http://kubernetes.io/docs/user-guide/annotations"

**Note:** This function appends passed data to existing values

### fn metadata.withClusterName

```ts
withClusterName(clusterName)
```

"The name of the cluster which the object belongs to. This is used to distinguish resources with same name and namespace in different clusters. This field is not set anywhere right now and apiserver is going to ignore it if set in create or update request."

### fn metadata.withCreationTimestamp

```ts
withCreationTimestamp(creationTimestamp)
```

"Time is a wrapper around time.Time which supports correct marshaling to YAML and JSON.  Wrappers are provided for many of the factory methods that the time package offers."

### fn metadata.withDeletionGracePeriodSeconds

```ts
withDeletionGracePeriodSeconds(deletionGracePeriodSeconds)
```

"Number of seconds allowed for this object to gracefully terminate before it will be removed from the system. Only set when deletionTimestamp is also set. May only be shortened. Read-only."

### fn metadata.withDeletionTimestamp

```ts
withDeletionTimestamp(deletionTimestamp)
```

"Time is a wrapper around time.Time which supports correct marshaling to YAML and JSON.  Wrappers are provided for many of the factory methods that the time package offers."

### fn metadata.withFinalizers

```ts
withFinalizers(finalizers)
```

"Must be empty before the object is deleted from the registry. Each entry is an identifier for the responsible component that will remove the entry from the list. If the deletionTimestamp of the object is non-nil, entries in this list can only be removed. Finalizers may be processed and removed in any order.  Order is NOT enforced because it introduces significant risk of stuck finalizers. finalizers is a shared field, any actor with permission can reorder it. If the finalizer list is processed in order, then this can lead to a situation in which the component responsible for the first finalizer in the list is waiting for a signal (field value, external system, or other) produced by a component responsible for a finalizer later in the list, resulting in a deadlock. Without enforced ordering finalizers are free to order amongst themselves and are not vulnerable to ordering changes in the list."

### fn metadata.withFinalizersMixin

```ts
withFinalizersMixin(finalizers)
```

"Must be empty before the object is deleted from the registry. Each entry is an identifier for the responsible component that will remove the entry from the list. If the deletionTimestamp of the object is non-nil, entries in this list can only be removed. Finalizers may be processed and removed in any order.  Order is NOT enforced because it introduces significant risk of stuck finalizers. finalizers is a shared field, any actor with permission can reorder it. If the finalizer list is processed in order, then this can lead to a situation in which the component responsible for the first finalizer in the list is waiting for a signal (field value, external system, or other) produced by a component responsible for a finalizer later in the list, resulting in a deadlock. Without enforced ordering finalizers are free to order amongst themselves and are not vulnerable to ordering changes in the list."

**Note:** This function appends passed data to existing values

### fn metadata.withGenerateName

```ts
withGenerateName(generateName)
```

"GenerateName is an optional prefix, used by the server, to generate a unique name ONLY IF the Name field has not been provided. If this field is used, the name returned to the client will be different than the name passed. This value will also be combined with a unique suffix. The provided value has the same validation rules as the Name field, and may be truncated by the length of the suffix required to make the value unique on the server.\n\nIf this field is specified and the generated name exists, the server will NOT return a 409 - instead, it will either return 201 Created or 500 with Reason ServerTimeout indicating a unique name could not be found in the time allotted, and the client should retry (optionally after the time indicated in the Retry-After header).\n\nApplied only if Name is not specified. More info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#idempotency"

### fn metadata.withGeneration

```ts
withGeneration(generation)
```

"A sequence number representing a specific generation of the desired state. Populated by the system. Read-only."

### fn metadata.withLabels

```ts
withLabels(labels)
```

"Map of string keys and values that can be used to organize and categorize (scope and select) objects. May match selectors of replication controllers and services. More info: http://kubernetes.io/docs/user-guide/labels"

### fn metadata.withLabelsMixin

```ts
withLabelsMixin(labels)
```

"Map of string keys and values that can be used to organize and categorize (scope and select) objects. May match selectors of replication controllers and services. More info: http://kubernetes.io/docs/user-guide/labels"

**Note:** This function appends passed data to existing values

### fn metadata.withName

```ts
withName(name)
```

"Name must be unique within a namespace. Is required when creating resources, although some resources may allow a client to request the generation of an appropriate name automatically. Name is primarily intended for creation idempotence and configuration definition. Cannot be updated. More info: http://kubernetes.io/docs/user-guide/identifiers#names"

### fn metadata.withNamespace

```ts
withNamespace(namespace)
```

"Namespace defines the space within which each name must be unique. An empty namespace is equivalent to the \"default\" namespace, but \"default\" is the canonical representation. Not all objects are required to be scoped to a namespace - the value of this field for those objects will be empty.\n\nMust be a DNS_LABEL. Cannot be updated. More info: http://kubernetes.io/docs/user-guide/namespaces"

### fn metadata.withOwnerReferences

```ts
withOwnerReferences(ownerReferences)
```

"List of objects depended by this object. If ALL objects in the list have been deleted, this object will be garbage collected. If this object is managed by a controller, then an entry in this list will point to this controller, with the controller field set to true. There cannot be more than one managing controller."

### fn metadata.withOwnerReferencesMixin

```ts
withOwnerReferencesMixin(ownerReferences)
```

"List of objects depended by this object. If ALL objects in the list have been deleted, this object will be garbage collected. If this object is managed by a controller, then an entry in this list will point to this controller, with the controller field set to true. There cannot be more than one managing controller."

**Note:** This function appends passed data to existing values

### fn metadata.withResourceVersion

```ts
withResourceVersion(resourceVersion)
```

"An opaque value that represents the internal version of this object that can be used by clients to determine when objects have changed. May be used for optimistic concurrency, change detection, and the watch operation on a resource or set of resources. Clients must treat these values as opaque and passed unmodified back to the server. They may only be valid for a particular resource or set of resources.\n\nPopulated by the system. Read-only. Value must be treated as opaque by clients and . More info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#concurrency-control-and-consistency"

### fn metadata.withSelfLink

```ts
withSelfLink(selfLink)
```

"SelfLink is a URL representing this object. Populated by the system. Read-only.\n\nDEPRECATED Kubernetes will stop propagating this field in 1.20 release and the field is planned to be removed in 1.21 release."

### fn metadata.withUid

```ts
withUid(uid)
```

"UID is the unique in time and space value for this object. It is typically generated by the server on successful creation of a resource and is not allowed to change on PUT operations.\n\nPopulated by the system. Read-only. More info: http://kubernetes.io/docs/user-guide/identifiers#uids"

## obj spec



### fn spec.withConfig

```ts
withConfig(config)
```



### fn spec.withConfigMixin

```ts
withConfigMixin(config)
```



**Note:** This function appends passed data to existing values

## obj spec.components



### fn spec.components.withCommands

```ts
withCommands(commands)
```



### fn spec.components.withCommandsMixin

```ts
withCommandsMixin(commands)
```



**Note:** This function appends passed data to existing values

### fn spec.components.withDisableMetric

```ts
withDisableMetric(disableMetric)
```



### fn spec.components.withEnableRollingUpdate

```ts
withEnableRollingUpdate(enableRollingUpdate)
```



### fn spec.components.withEnv

```ts
withEnv(env)
```



### fn spec.components.withEnvMixin

```ts
withEnvMixin(env)
```



**Note:** This function appends passed data to existing values

### fn spec.components.withImage

```ts
withImage(image)
```



### fn spec.components.withImagePullPolicy

```ts
withImagePullPolicy(imagePullPolicy)
```



### fn spec.components.withImagePullSecrets

```ts
withImagePullSecrets(imagePullSecrets)
```



### fn spec.components.withImagePullSecretsMixin

```ts
withImagePullSecretsMixin(imagePullSecrets)
```



**Note:** This function appends passed data to existing values

### fn spec.components.withImageUpdateMode

```ts
withImageUpdateMode(imageUpdateMode)
```



### fn spec.components.withMetricInterval

```ts
withMetricInterval(metricInterval)
```



### fn spec.components.withNodeSelector

```ts
withNodeSelector(nodeSelector)
```



### fn spec.components.withNodeSelectorMixin

```ts
withNodeSelectorMixin(nodeSelector)
```



**Note:** This function appends passed data to existing values

### fn spec.components.withPaused

```ts
withPaused(paused)
```



### fn spec.components.withPodAnnotations

```ts
withPodAnnotations(podAnnotations)
```



### fn spec.components.withPodAnnotationsMixin

```ts
withPodAnnotationsMixin(podAnnotations)
```



**Note:** This function appends passed data to existing values

### fn spec.components.withPodLabels

```ts
withPodLabels(podLabels)
```



### fn spec.components.withPodLabelsMixin

```ts
withPodLabelsMixin(podLabels)
```



**Note:** This function appends passed data to existing values

### fn spec.components.withPriorityClassName

```ts
withPriorityClassName(priorityClassName)
```



### fn spec.components.withRunWithSubProcess

```ts
withRunWithSubProcess(runWithSubProcess)
```



### fn spec.components.withSchedulerName

```ts
withSchedulerName(schedulerName)
```



### fn spec.components.withServiceAccountName

```ts
withServiceAccountName(serviceAccountName)
```



### fn spec.components.withTolerations

```ts
withTolerations(tolerations)
```



### fn spec.components.withTolerationsMixin

```ts
withTolerationsMixin(tolerations)
```



**Note:** This function appends passed data to existing values

### fn spec.components.withToolImage

```ts
withToolImage(toolImage)
```



### fn spec.components.withUpdateConfigMapOnly

```ts
withUpdateConfigMapOnly(updateConfigMapOnly)
```



### fn spec.components.withUpdateToolImage

```ts
withUpdateToolImage(updateToolImage)
```



### fn spec.components.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```



### fn spec.components.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```



**Note:** This function appends passed data to existing values

### fn spec.components.withVolumes

```ts
withVolumes(volumes)
```



### fn spec.components.withVolumesMixin

```ts
withVolumesMixin(volumes)
```



**Note:** This function appends passed data to existing values

## obj spec.components.affinity



## obj spec.components.affinity.nodeAffinity



### fn spec.components.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference



### fn spec.components.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.components.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.components.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions



### fn spec.components.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields



### fn spec.components.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withKey

```ts
withKey(key)
```



### fn spec.components.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.components.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValues

```ts
withValues(values)
```



### fn spec.components.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTerms

```ts
withNodeSelectorTerms(nodeSelectorTerms)
```



### fn spec.components.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTermsMixin

```ts
withNodeSelectorTermsMixin(nodeSelectorTerms)
```



**Note:** This function appends passed data to existing values

## obj spec.components.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms



### fn spec.components.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.components.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.components.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions



### fn spec.components.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields



### fn spec.components.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withKey

```ts
withKey(key)
```



### fn spec.components.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.components.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValues

```ts
withValues(values)
```



### fn spec.components.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.affinity.podAffinity



### fn spec.components.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.components.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.components.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.components.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.components.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.components.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.affinity.podAntiAffinity



### fn spec.components.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.components.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.components.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.components.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.components.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.components.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataCoord



### fn spec.components.dataCoord.withCommands

```ts
withCommands(commands)
```



### fn spec.components.dataCoord.withCommandsMixin

```ts
withCommandsMixin(commands)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataCoord.withEnv

```ts
withEnv(env)
```



### fn spec.components.dataCoord.withEnvMixin

```ts
withEnvMixin(env)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataCoord.withImage

```ts
withImage(image)
```



### fn spec.components.dataCoord.withImagePullPolicy

```ts
withImagePullPolicy(imagePullPolicy)
```



### fn spec.components.dataCoord.withImagePullSecrets

```ts
withImagePullSecrets(imagePullSecrets)
```



### fn spec.components.dataCoord.withImagePullSecretsMixin

```ts
withImagePullSecretsMixin(imagePullSecrets)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataCoord.withInitContainers

```ts
withInitContainers(initContainers)
```



### fn spec.components.dataCoord.withInitContainersMixin

```ts
withInitContainersMixin(initContainers)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataCoord.withNodeSelector

```ts
withNodeSelector(nodeSelector)
```



### fn spec.components.dataCoord.withNodeSelectorMixin

```ts
withNodeSelectorMixin(nodeSelector)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataCoord.withPaused

```ts
withPaused(paused)
```



### fn spec.components.dataCoord.withPodAnnotations

```ts
withPodAnnotations(podAnnotations)
```



### fn spec.components.dataCoord.withPodAnnotationsMixin

```ts
withPodAnnotationsMixin(podAnnotations)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataCoord.withPodLabels

```ts
withPodLabels(podLabels)
```



### fn spec.components.dataCoord.withPodLabelsMixin

```ts
withPodLabelsMixin(podLabels)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataCoord.withPort

```ts
withPort(port)
```



### fn spec.components.dataCoord.withPriorityClassName

```ts
withPriorityClassName(priorityClassName)
```



### fn spec.components.dataCoord.withReplicas

```ts
withReplicas(replicas)
```



### fn spec.components.dataCoord.withRunWithSubProcess

```ts
withRunWithSubProcess(runWithSubProcess)
```



### fn spec.components.dataCoord.withSchedulerName

```ts
withSchedulerName(schedulerName)
```



### fn spec.components.dataCoord.withServiceAccountName

```ts
withServiceAccountName(serviceAccountName)
```



### fn spec.components.dataCoord.withSidecars

```ts
withSidecars(sidecars)
```



### fn spec.components.dataCoord.withSidecarsMixin

```ts
withSidecarsMixin(sidecars)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataCoord.withTolerations

```ts
withTolerations(tolerations)
```



### fn spec.components.dataCoord.withTolerationsMixin

```ts
withTolerationsMixin(tolerations)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataCoord.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```



### fn spec.components.dataCoord.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataCoord.withVolumes

```ts
withVolumes(volumes)
```



### fn spec.components.dataCoord.withVolumesMixin

```ts
withVolumesMixin(volumes)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataCoord.affinity



## obj spec.components.dataCoord.affinity.nodeAffinity



### fn spec.components.dataCoord.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.dataCoord.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.dataCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.dataCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference



### fn spec.components.dataCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.dataCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.components.dataCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions



### fn spec.components.dataCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.dataCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.dataCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.dataCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields



### fn spec.components.dataCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withKey

```ts
withKey(key)
```



### fn spec.components.dataCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.components.dataCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValues

```ts
withValues(values)
```



### fn spec.components.dataCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.dataCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTerms

```ts
withNodeSelectorTerms(nodeSelectorTerms)
```



### fn spec.components.dataCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTermsMixin

```ts
withNodeSelectorTermsMixin(nodeSelectorTerms)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms



### fn spec.components.dataCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.dataCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.components.dataCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions



### fn spec.components.dataCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.dataCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.dataCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.dataCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields



### fn spec.components.dataCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withKey

```ts
withKey(key)
```



### fn spec.components.dataCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.components.dataCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValues

```ts
withValues(values)
```



### fn spec.components.dataCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataCoord.affinity.podAffinity



### fn spec.components.dataCoord.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.dataCoord.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataCoord.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.dataCoord.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.dataCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.dataCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.dataCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.dataCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.components.dataCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.dataCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.dataCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.components.dataCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.dataCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.dataCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.dataCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.components.dataCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.dataCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.dataCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.components.dataCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.dataCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.dataCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.dataCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataCoord.affinity.podAntiAffinity



### fn spec.components.dataCoord.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.dataCoord.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataCoord.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.dataCoord.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.dataCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.dataCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.dataCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.dataCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.components.dataCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.dataCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.dataCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.components.dataCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.dataCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.dataCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.dataCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.components.dataCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.dataCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.dataCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.components.dataCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.dataCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.dataCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.dataCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataCoord.env



### fn spec.components.dataCoord.env.withName

```ts
withName(name)
```



### fn spec.components.dataCoord.env.withValue

```ts
withValue(value)
```



## obj spec.components.dataCoord.env.valueFrom



## obj spec.components.dataCoord.env.valueFrom.configMapKeyRef



### fn spec.components.dataCoord.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```



### fn spec.components.dataCoord.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```



### fn spec.components.dataCoord.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.components.dataCoord.env.valueFrom.fieldRef



### fn spec.components.dataCoord.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.components.dataCoord.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.components.dataCoord.env.valueFrom.resourceFieldRef



### fn spec.components.dataCoord.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.components.dataCoord.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.components.dataCoord.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.components.dataCoord.env.valueFrom.secretKeyRef



### fn spec.components.dataCoord.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```



### fn spec.components.dataCoord.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```



### fn spec.components.dataCoord.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.components.dataCoord.imagePullSecrets



### fn spec.components.dataCoord.imagePullSecrets.withName

```ts
withName(name)
```



## obj spec.components.dataCoord.resources



### fn spec.components.dataCoord.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.components.dataCoord.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataCoord.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.components.dataCoord.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataCoord.tolerations



### fn spec.components.dataCoord.tolerations.withEffect

```ts
withEffect(effect)
```



### fn spec.components.dataCoord.tolerations.withKey

```ts
withKey(key)
```



### fn spec.components.dataCoord.tolerations.withOperator

```ts
withOperator(operator)
```



### fn spec.components.dataCoord.tolerations.withTolerationSeconds

```ts
withTolerationSeconds(tolerationSeconds)
```



### fn spec.components.dataCoord.tolerations.withValue

```ts
withValue(value)
```



## obj spec.components.dataCoord.volumeMounts



### fn spec.components.dataCoord.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```



### fn spec.components.dataCoord.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```



### fn spec.components.dataCoord.volumeMounts.withName

```ts
withName(name)
```



### fn spec.components.dataCoord.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.components.dataCoord.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```



### fn spec.components.dataCoord.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```



## obj spec.components.dataNode



### fn spec.components.dataNode.withCommands

```ts
withCommands(commands)
```



### fn spec.components.dataNode.withCommandsMixin

```ts
withCommandsMixin(commands)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataNode.withEnv

```ts
withEnv(env)
```



### fn spec.components.dataNode.withEnvMixin

```ts
withEnvMixin(env)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataNode.withImage

```ts
withImage(image)
```



### fn spec.components.dataNode.withImagePullPolicy

```ts
withImagePullPolicy(imagePullPolicy)
```



### fn spec.components.dataNode.withImagePullSecrets

```ts
withImagePullSecrets(imagePullSecrets)
```



### fn spec.components.dataNode.withImagePullSecretsMixin

```ts
withImagePullSecretsMixin(imagePullSecrets)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataNode.withInitContainers

```ts
withInitContainers(initContainers)
```



### fn spec.components.dataNode.withInitContainersMixin

```ts
withInitContainersMixin(initContainers)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataNode.withNodeSelector

```ts
withNodeSelector(nodeSelector)
```



### fn spec.components.dataNode.withNodeSelectorMixin

```ts
withNodeSelectorMixin(nodeSelector)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataNode.withPaused

```ts
withPaused(paused)
```



### fn spec.components.dataNode.withPodAnnotations

```ts
withPodAnnotations(podAnnotations)
```



### fn spec.components.dataNode.withPodAnnotationsMixin

```ts
withPodAnnotationsMixin(podAnnotations)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataNode.withPodLabels

```ts
withPodLabels(podLabels)
```



### fn spec.components.dataNode.withPodLabelsMixin

```ts
withPodLabelsMixin(podLabels)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataNode.withPort

```ts
withPort(port)
```



### fn spec.components.dataNode.withPriorityClassName

```ts
withPriorityClassName(priorityClassName)
```



### fn spec.components.dataNode.withReplicas

```ts
withReplicas(replicas)
```



### fn spec.components.dataNode.withRunWithSubProcess

```ts
withRunWithSubProcess(runWithSubProcess)
```



### fn spec.components.dataNode.withSchedulerName

```ts
withSchedulerName(schedulerName)
```



### fn spec.components.dataNode.withServiceAccountName

```ts
withServiceAccountName(serviceAccountName)
```



### fn spec.components.dataNode.withSidecars

```ts
withSidecars(sidecars)
```



### fn spec.components.dataNode.withSidecarsMixin

```ts
withSidecarsMixin(sidecars)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataNode.withTolerations

```ts
withTolerations(tolerations)
```



### fn spec.components.dataNode.withTolerationsMixin

```ts
withTolerationsMixin(tolerations)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataNode.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```



### fn spec.components.dataNode.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataNode.withVolumes

```ts
withVolumes(volumes)
```



### fn spec.components.dataNode.withVolumesMixin

```ts
withVolumesMixin(volumes)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataNode.affinity



## obj spec.components.dataNode.affinity.nodeAffinity



### fn spec.components.dataNode.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.dataNode.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.dataNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.dataNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference



### fn spec.components.dataNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.dataNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.components.dataNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions



### fn spec.components.dataNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.dataNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.dataNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.dataNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields



### fn spec.components.dataNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withKey

```ts
withKey(key)
```



### fn spec.components.dataNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.components.dataNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValues

```ts
withValues(values)
```



### fn spec.components.dataNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.dataNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTerms

```ts
withNodeSelectorTerms(nodeSelectorTerms)
```



### fn spec.components.dataNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTermsMixin

```ts
withNodeSelectorTermsMixin(nodeSelectorTerms)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms



### fn spec.components.dataNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.dataNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.components.dataNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions



### fn spec.components.dataNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.dataNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.dataNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.dataNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields



### fn spec.components.dataNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withKey

```ts
withKey(key)
```



### fn spec.components.dataNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.components.dataNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValues

```ts
withValues(values)
```



### fn spec.components.dataNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataNode.affinity.podAffinity



### fn spec.components.dataNode.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.dataNode.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataNode.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.dataNode.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.dataNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.dataNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.dataNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.dataNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.components.dataNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.dataNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.dataNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.components.dataNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.dataNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.dataNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.dataNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.components.dataNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.dataNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.dataNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.components.dataNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.dataNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.dataNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.dataNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataNode.affinity.podAntiAffinity



### fn spec.components.dataNode.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.dataNode.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataNode.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.dataNode.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.dataNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.dataNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.dataNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.dataNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.components.dataNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.dataNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.dataNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.components.dataNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.dataNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.dataNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.dataNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.components.dataNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.dataNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.dataNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.components.dataNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.dataNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.dataNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.dataNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataNode.env



### fn spec.components.dataNode.env.withName

```ts
withName(name)
```



### fn spec.components.dataNode.env.withValue

```ts
withValue(value)
```



## obj spec.components.dataNode.env.valueFrom



## obj spec.components.dataNode.env.valueFrom.configMapKeyRef



### fn spec.components.dataNode.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```



### fn spec.components.dataNode.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```



### fn spec.components.dataNode.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.components.dataNode.env.valueFrom.fieldRef



### fn spec.components.dataNode.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.components.dataNode.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.components.dataNode.env.valueFrom.resourceFieldRef



### fn spec.components.dataNode.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.components.dataNode.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.components.dataNode.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.components.dataNode.env.valueFrom.secretKeyRef



### fn spec.components.dataNode.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```



### fn spec.components.dataNode.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```



### fn spec.components.dataNode.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.components.dataNode.imagePullSecrets



### fn spec.components.dataNode.imagePullSecrets.withName

```ts
withName(name)
```



## obj spec.components.dataNode.resources



### fn spec.components.dataNode.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.components.dataNode.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.components.dataNode.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.components.dataNode.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.components.dataNode.tolerations



### fn spec.components.dataNode.tolerations.withEffect

```ts
withEffect(effect)
```



### fn spec.components.dataNode.tolerations.withKey

```ts
withKey(key)
```



### fn spec.components.dataNode.tolerations.withOperator

```ts
withOperator(operator)
```



### fn spec.components.dataNode.tolerations.withTolerationSeconds

```ts
withTolerationSeconds(tolerationSeconds)
```



### fn spec.components.dataNode.tolerations.withValue

```ts
withValue(value)
```



## obj spec.components.dataNode.volumeMounts



### fn spec.components.dataNode.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```



### fn spec.components.dataNode.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```



### fn spec.components.dataNode.volumeMounts.withName

```ts
withName(name)
```



### fn spec.components.dataNode.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.components.dataNode.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```



### fn spec.components.dataNode.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```



## obj spec.components.env



### fn spec.components.env.withName

```ts
withName(name)
```



### fn spec.components.env.withValue

```ts
withValue(value)
```



## obj spec.components.env.valueFrom



## obj spec.components.env.valueFrom.configMapKeyRef



### fn spec.components.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```



### fn spec.components.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```



### fn spec.components.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.components.env.valueFrom.fieldRef



### fn spec.components.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.components.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.components.env.valueFrom.resourceFieldRef



### fn spec.components.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.components.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.components.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.components.env.valueFrom.secretKeyRef



### fn spec.components.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```



### fn spec.components.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```



### fn spec.components.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.components.imagePullSecrets



### fn spec.components.imagePullSecrets.withName

```ts
withName(name)
```



## obj spec.components.indexCoord



### fn spec.components.indexCoord.withCommands

```ts
withCommands(commands)
```



### fn spec.components.indexCoord.withCommandsMixin

```ts
withCommandsMixin(commands)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexCoord.withEnv

```ts
withEnv(env)
```



### fn spec.components.indexCoord.withEnvMixin

```ts
withEnvMixin(env)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexCoord.withImage

```ts
withImage(image)
```



### fn spec.components.indexCoord.withImagePullPolicy

```ts
withImagePullPolicy(imagePullPolicy)
```



### fn spec.components.indexCoord.withImagePullSecrets

```ts
withImagePullSecrets(imagePullSecrets)
```



### fn spec.components.indexCoord.withImagePullSecretsMixin

```ts
withImagePullSecretsMixin(imagePullSecrets)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexCoord.withInitContainers

```ts
withInitContainers(initContainers)
```



### fn spec.components.indexCoord.withInitContainersMixin

```ts
withInitContainersMixin(initContainers)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexCoord.withNodeSelector

```ts
withNodeSelector(nodeSelector)
```



### fn spec.components.indexCoord.withNodeSelectorMixin

```ts
withNodeSelectorMixin(nodeSelector)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexCoord.withPaused

```ts
withPaused(paused)
```



### fn spec.components.indexCoord.withPodAnnotations

```ts
withPodAnnotations(podAnnotations)
```



### fn spec.components.indexCoord.withPodAnnotationsMixin

```ts
withPodAnnotationsMixin(podAnnotations)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexCoord.withPodLabels

```ts
withPodLabels(podLabels)
```



### fn spec.components.indexCoord.withPodLabelsMixin

```ts
withPodLabelsMixin(podLabels)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexCoord.withPort

```ts
withPort(port)
```



### fn spec.components.indexCoord.withPriorityClassName

```ts
withPriorityClassName(priorityClassName)
```



### fn spec.components.indexCoord.withReplicas

```ts
withReplicas(replicas)
```



### fn spec.components.indexCoord.withRunWithSubProcess

```ts
withRunWithSubProcess(runWithSubProcess)
```



### fn spec.components.indexCoord.withSchedulerName

```ts
withSchedulerName(schedulerName)
```



### fn spec.components.indexCoord.withServiceAccountName

```ts
withServiceAccountName(serviceAccountName)
```



### fn spec.components.indexCoord.withSidecars

```ts
withSidecars(sidecars)
```



### fn spec.components.indexCoord.withSidecarsMixin

```ts
withSidecarsMixin(sidecars)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexCoord.withTolerations

```ts
withTolerations(tolerations)
```



### fn spec.components.indexCoord.withTolerationsMixin

```ts
withTolerationsMixin(tolerations)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexCoord.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```



### fn spec.components.indexCoord.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexCoord.withVolumes

```ts
withVolumes(volumes)
```



### fn spec.components.indexCoord.withVolumesMixin

```ts
withVolumesMixin(volumes)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexCoord.affinity



## obj spec.components.indexCoord.affinity.nodeAffinity



### fn spec.components.indexCoord.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.indexCoord.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.indexCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.indexCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference



### fn spec.components.indexCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.indexCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.components.indexCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions



### fn spec.components.indexCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.indexCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.indexCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.indexCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields



### fn spec.components.indexCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withKey

```ts
withKey(key)
```



### fn spec.components.indexCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.components.indexCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValues

```ts
withValues(values)
```



### fn spec.components.indexCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.indexCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTerms

```ts
withNodeSelectorTerms(nodeSelectorTerms)
```



### fn spec.components.indexCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTermsMixin

```ts
withNodeSelectorTermsMixin(nodeSelectorTerms)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms



### fn spec.components.indexCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.indexCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.components.indexCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions



### fn spec.components.indexCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.indexCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.indexCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.indexCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields



### fn spec.components.indexCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withKey

```ts
withKey(key)
```



### fn spec.components.indexCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.components.indexCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValues

```ts
withValues(values)
```



### fn spec.components.indexCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexCoord.affinity.podAffinity



### fn spec.components.indexCoord.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.indexCoord.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexCoord.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.indexCoord.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.indexCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.indexCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.indexCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.indexCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.components.indexCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.indexCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.indexCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.components.indexCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.indexCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.indexCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.indexCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.components.indexCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.indexCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.indexCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.components.indexCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.indexCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.indexCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.indexCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexCoord.affinity.podAntiAffinity



### fn spec.components.indexCoord.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.indexCoord.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexCoord.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.indexCoord.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.indexCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.indexCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.indexCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.indexCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.components.indexCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.indexCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.indexCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.components.indexCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.indexCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.indexCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.indexCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.components.indexCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.indexCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.indexCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.components.indexCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.indexCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.indexCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.indexCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexCoord.env



### fn spec.components.indexCoord.env.withName

```ts
withName(name)
```



### fn spec.components.indexCoord.env.withValue

```ts
withValue(value)
```



## obj spec.components.indexCoord.env.valueFrom



## obj spec.components.indexCoord.env.valueFrom.configMapKeyRef



### fn spec.components.indexCoord.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```



### fn spec.components.indexCoord.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```



### fn spec.components.indexCoord.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.components.indexCoord.env.valueFrom.fieldRef



### fn spec.components.indexCoord.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.components.indexCoord.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.components.indexCoord.env.valueFrom.resourceFieldRef



### fn spec.components.indexCoord.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.components.indexCoord.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.components.indexCoord.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.components.indexCoord.env.valueFrom.secretKeyRef



### fn spec.components.indexCoord.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```



### fn spec.components.indexCoord.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```



### fn spec.components.indexCoord.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.components.indexCoord.imagePullSecrets



### fn spec.components.indexCoord.imagePullSecrets.withName

```ts
withName(name)
```



## obj spec.components.indexCoord.resources



### fn spec.components.indexCoord.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.components.indexCoord.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexCoord.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.components.indexCoord.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexCoord.tolerations



### fn spec.components.indexCoord.tolerations.withEffect

```ts
withEffect(effect)
```



### fn spec.components.indexCoord.tolerations.withKey

```ts
withKey(key)
```



### fn spec.components.indexCoord.tolerations.withOperator

```ts
withOperator(operator)
```



### fn spec.components.indexCoord.tolerations.withTolerationSeconds

```ts
withTolerationSeconds(tolerationSeconds)
```



### fn spec.components.indexCoord.tolerations.withValue

```ts
withValue(value)
```



## obj spec.components.indexCoord.volumeMounts



### fn spec.components.indexCoord.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```



### fn spec.components.indexCoord.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```



### fn spec.components.indexCoord.volumeMounts.withName

```ts
withName(name)
```



### fn spec.components.indexCoord.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.components.indexCoord.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```



### fn spec.components.indexCoord.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```



## obj spec.components.indexNode



### fn spec.components.indexNode.withCommands

```ts
withCommands(commands)
```



### fn spec.components.indexNode.withCommandsMixin

```ts
withCommandsMixin(commands)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexNode.withEnv

```ts
withEnv(env)
```



### fn spec.components.indexNode.withEnvMixin

```ts
withEnvMixin(env)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexNode.withImage

```ts
withImage(image)
```



### fn spec.components.indexNode.withImagePullPolicy

```ts
withImagePullPolicy(imagePullPolicy)
```



### fn spec.components.indexNode.withImagePullSecrets

```ts
withImagePullSecrets(imagePullSecrets)
```



### fn spec.components.indexNode.withImagePullSecretsMixin

```ts
withImagePullSecretsMixin(imagePullSecrets)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexNode.withInitContainers

```ts
withInitContainers(initContainers)
```



### fn spec.components.indexNode.withInitContainersMixin

```ts
withInitContainersMixin(initContainers)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexNode.withNodeSelector

```ts
withNodeSelector(nodeSelector)
```



### fn spec.components.indexNode.withNodeSelectorMixin

```ts
withNodeSelectorMixin(nodeSelector)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexNode.withPaused

```ts
withPaused(paused)
```



### fn spec.components.indexNode.withPodAnnotations

```ts
withPodAnnotations(podAnnotations)
```



### fn spec.components.indexNode.withPodAnnotationsMixin

```ts
withPodAnnotationsMixin(podAnnotations)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexNode.withPodLabels

```ts
withPodLabels(podLabels)
```



### fn spec.components.indexNode.withPodLabelsMixin

```ts
withPodLabelsMixin(podLabels)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexNode.withPort

```ts
withPort(port)
```



### fn spec.components.indexNode.withPriorityClassName

```ts
withPriorityClassName(priorityClassName)
```



### fn spec.components.indexNode.withReplicas

```ts
withReplicas(replicas)
```



### fn spec.components.indexNode.withRunWithSubProcess

```ts
withRunWithSubProcess(runWithSubProcess)
```



### fn spec.components.indexNode.withSchedulerName

```ts
withSchedulerName(schedulerName)
```



### fn spec.components.indexNode.withServiceAccountName

```ts
withServiceAccountName(serviceAccountName)
```



### fn spec.components.indexNode.withSidecars

```ts
withSidecars(sidecars)
```



### fn spec.components.indexNode.withSidecarsMixin

```ts
withSidecarsMixin(sidecars)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexNode.withTolerations

```ts
withTolerations(tolerations)
```



### fn spec.components.indexNode.withTolerationsMixin

```ts
withTolerationsMixin(tolerations)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexNode.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```



### fn spec.components.indexNode.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexNode.withVolumes

```ts
withVolumes(volumes)
```



### fn spec.components.indexNode.withVolumesMixin

```ts
withVolumesMixin(volumes)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexNode.affinity



## obj spec.components.indexNode.affinity.nodeAffinity



### fn spec.components.indexNode.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.indexNode.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.indexNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.indexNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference



### fn spec.components.indexNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.indexNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.components.indexNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions



### fn spec.components.indexNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.indexNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.indexNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.indexNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields



### fn spec.components.indexNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withKey

```ts
withKey(key)
```



### fn spec.components.indexNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.components.indexNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValues

```ts
withValues(values)
```



### fn spec.components.indexNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.indexNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTerms

```ts
withNodeSelectorTerms(nodeSelectorTerms)
```



### fn spec.components.indexNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTermsMixin

```ts
withNodeSelectorTermsMixin(nodeSelectorTerms)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms



### fn spec.components.indexNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.indexNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.components.indexNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions



### fn spec.components.indexNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.indexNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.indexNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.indexNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields



### fn spec.components.indexNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withKey

```ts
withKey(key)
```



### fn spec.components.indexNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.components.indexNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValues

```ts
withValues(values)
```



### fn spec.components.indexNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexNode.affinity.podAffinity



### fn spec.components.indexNode.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.indexNode.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexNode.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.indexNode.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.indexNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.indexNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.indexNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.indexNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.components.indexNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.indexNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.indexNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.components.indexNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.indexNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.indexNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.indexNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.components.indexNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.indexNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.indexNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.components.indexNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.indexNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.indexNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.indexNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexNode.affinity.podAntiAffinity



### fn spec.components.indexNode.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.indexNode.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexNode.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.indexNode.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.indexNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.indexNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.indexNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.indexNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.components.indexNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.indexNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.indexNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.components.indexNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.indexNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.indexNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.indexNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.components.indexNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.indexNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.indexNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.components.indexNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.indexNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.indexNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.indexNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexNode.env



### fn spec.components.indexNode.env.withName

```ts
withName(name)
```



### fn spec.components.indexNode.env.withValue

```ts
withValue(value)
```



## obj spec.components.indexNode.env.valueFrom



## obj spec.components.indexNode.env.valueFrom.configMapKeyRef



### fn spec.components.indexNode.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```



### fn spec.components.indexNode.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```



### fn spec.components.indexNode.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.components.indexNode.env.valueFrom.fieldRef



### fn spec.components.indexNode.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.components.indexNode.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.components.indexNode.env.valueFrom.resourceFieldRef



### fn spec.components.indexNode.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.components.indexNode.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.components.indexNode.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.components.indexNode.env.valueFrom.secretKeyRef



### fn spec.components.indexNode.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```



### fn spec.components.indexNode.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```



### fn spec.components.indexNode.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.components.indexNode.imagePullSecrets



### fn spec.components.indexNode.imagePullSecrets.withName

```ts
withName(name)
```



## obj spec.components.indexNode.resources



### fn spec.components.indexNode.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.components.indexNode.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.components.indexNode.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.components.indexNode.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.components.indexNode.tolerations



### fn spec.components.indexNode.tolerations.withEffect

```ts
withEffect(effect)
```



### fn spec.components.indexNode.tolerations.withKey

```ts
withKey(key)
```



### fn spec.components.indexNode.tolerations.withOperator

```ts
withOperator(operator)
```



### fn spec.components.indexNode.tolerations.withTolerationSeconds

```ts
withTolerationSeconds(tolerationSeconds)
```



### fn spec.components.indexNode.tolerations.withValue

```ts
withValue(value)
```



## obj spec.components.indexNode.volumeMounts



### fn spec.components.indexNode.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```



### fn spec.components.indexNode.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```



### fn spec.components.indexNode.volumeMounts.withName

```ts
withName(name)
```



### fn spec.components.indexNode.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.components.indexNode.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```



### fn spec.components.indexNode.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```



## obj spec.components.mixCoord



### fn spec.components.mixCoord.withCommands

```ts
withCommands(commands)
```



### fn spec.components.mixCoord.withCommandsMixin

```ts
withCommandsMixin(commands)
```



**Note:** This function appends passed data to existing values

### fn spec.components.mixCoord.withEnv

```ts
withEnv(env)
```



### fn spec.components.mixCoord.withEnvMixin

```ts
withEnvMixin(env)
```



**Note:** This function appends passed data to existing values

### fn spec.components.mixCoord.withImage

```ts
withImage(image)
```



### fn spec.components.mixCoord.withImagePullPolicy

```ts
withImagePullPolicy(imagePullPolicy)
```



### fn spec.components.mixCoord.withImagePullSecrets

```ts
withImagePullSecrets(imagePullSecrets)
```



### fn spec.components.mixCoord.withImagePullSecretsMixin

```ts
withImagePullSecretsMixin(imagePullSecrets)
```



**Note:** This function appends passed data to existing values

### fn spec.components.mixCoord.withInitContainers

```ts
withInitContainers(initContainers)
```



### fn spec.components.mixCoord.withInitContainersMixin

```ts
withInitContainersMixin(initContainers)
```



**Note:** This function appends passed data to existing values

### fn spec.components.mixCoord.withNodeSelector

```ts
withNodeSelector(nodeSelector)
```



### fn spec.components.mixCoord.withNodeSelectorMixin

```ts
withNodeSelectorMixin(nodeSelector)
```



**Note:** This function appends passed data to existing values

### fn spec.components.mixCoord.withPaused

```ts
withPaused(paused)
```



### fn spec.components.mixCoord.withPodAnnotations

```ts
withPodAnnotations(podAnnotations)
```



### fn spec.components.mixCoord.withPodAnnotationsMixin

```ts
withPodAnnotationsMixin(podAnnotations)
```



**Note:** This function appends passed data to existing values

### fn spec.components.mixCoord.withPodLabels

```ts
withPodLabels(podLabels)
```



### fn spec.components.mixCoord.withPodLabelsMixin

```ts
withPodLabelsMixin(podLabels)
```



**Note:** This function appends passed data to existing values

### fn spec.components.mixCoord.withPort

```ts
withPort(port)
```



### fn spec.components.mixCoord.withPriorityClassName

```ts
withPriorityClassName(priorityClassName)
```



### fn spec.components.mixCoord.withReplicas

```ts
withReplicas(replicas)
```



### fn spec.components.mixCoord.withRunWithSubProcess

```ts
withRunWithSubProcess(runWithSubProcess)
```



### fn spec.components.mixCoord.withSchedulerName

```ts
withSchedulerName(schedulerName)
```



### fn spec.components.mixCoord.withServiceAccountName

```ts
withServiceAccountName(serviceAccountName)
```



### fn spec.components.mixCoord.withSidecars

```ts
withSidecars(sidecars)
```



### fn spec.components.mixCoord.withSidecarsMixin

```ts
withSidecarsMixin(sidecars)
```



**Note:** This function appends passed data to existing values

### fn spec.components.mixCoord.withTolerations

```ts
withTolerations(tolerations)
```



### fn spec.components.mixCoord.withTolerationsMixin

```ts
withTolerationsMixin(tolerations)
```



**Note:** This function appends passed data to existing values

### fn spec.components.mixCoord.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```



### fn spec.components.mixCoord.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```



**Note:** This function appends passed data to existing values

### fn spec.components.mixCoord.withVolumes

```ts
withVolumes(volumes)
```



### fn spec.components.mixCoord.withVolumesMixin

```ts
withVolumesMixin(volumes)
```



**Note:** This function appends passed data to existing values

## obj spec.components.mixCoord.affinity



## obj spec.components.mixCoord.affinity.nodeAffinity



### fn spec.components.mixCoord.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.mixCoord.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.mixCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.mixCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.mixCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference



### fn spec.components.mixCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.mixCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.mixCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.components.mixCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.components.mixCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions



### fn spec.components.mixCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.mixCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.mixCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.mixCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.mixCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields



### fn spec.components.mixCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withKey

```ts
withKey(key)
```



### fn spec.components.mixCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.components.mixCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValues

```ts
withValues(values)
```



### fn spec.components.mixCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.mixCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.mixCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTerms

```ts
withNodeSelectorTerms(nodeSelectorTerms)
```



### fn spec.components.mixCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTermsMixin

```ts
withNodeSelectorTermsMixin(nodeSelectorTerms)
```



**Note:** This function appends passed data to existing values

## obj spec.components.mixCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms



### fn spec.components.mixCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.mixCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.mixCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.components.mixCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.components.mixCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions



### fn spec.components.mixCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.mixCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.mixCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.mixCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.mixCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields



### fn spec.components.mixCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withKey

```ts
withKey(key)
```



### fn spec.components.mixCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.components.mixCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValues

```ts
withValues(values)
```



### fn spec.components.mixCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.mixCoord.affinity.podAffinity



### fn spec.components.mixCoord.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.mixCoord.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.components.mixCoord.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.mixCoord.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.mixCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.mixCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.mixCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.mixCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.mixCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.mixCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.components.mixCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.mixCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.mixCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.mixCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.mixCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.components.mixCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.mixCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.mixCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.mixCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.mixCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.components.mixCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.mixCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.mixCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.mixCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.mixCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.components.mixCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.mixCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.mixCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.mixCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.mixCoord.affinity.podAntiAffinity



### fn spec.components.mixCoord.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.mixCoord.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.components.mixCoord.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.mixCoord.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.mixCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.mixCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.mixCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.mixCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.mixCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.mixCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.components.mixCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.mixCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.mixCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.mixCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.mixCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.components.mixCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.mixCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.mixCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.mixCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.mixCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.components.mixCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.mixCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.mixCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.mixCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.mixCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.components.mixCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.mixCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.mixCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.mixCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.mixCoord.env



### fn spec.components.mixCoord.env.withName

```ts
withName(name)
```



### fn spec.components.mixCoord.env.withValue

```ts
withValue(value)
```



## obj spec.components.mixCoord.env.valueFrom



## obj spec.components.mixCoord.env.valueFrom.configMapKeyRef



### fn spec.components.mixCoord.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```



### fn spec.components.mixCoord.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```



### fn spec.components.mixCoord.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.components.mixCoord.env.valueFrom.fieldRef



### fn spec.components.mixCoord.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.components.mixCoord.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.components.mixCoord.env.valueFrom.resourceFieldRef



### fn spec.components.mixCoord.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.components.mixCoord.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.components.mixCoord.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.components.mixCoord.env.valueFrom.secretKeyRef



### fn spec.components.mixCoord.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```



### fn spec.components.mixCoord.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```



### fn spec.components.mixCoord.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.components.mixCoord.imagePullSecrets



### fn spec.components.mixCoord.imagePullSecrets.withName

```ts
withName(name)
```



## obj spec.components.mixCoord.resources



### fn spec.components.mixCoord.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.components.mixCoord.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.components.mixCoord.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.components.mixCoord.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.components.mixCoord.tolerations



### fn spec.components.mixCoord.tolerations.withEffect

```ts
withEffect(effect)
```



### fn spec.components.mixCoord.tolerations.withKey

```ts
withKey(key)
```



### fn spec.components.mixCoord.tolerations.withOperator

```ts
withOperator(operator)
```



### fn spec.components.mixCoord.tolerations.withTolerationSeconds

```ts
withTolerationSeconds(tolerationSeconds)
```



### fn spec.components.mixCoord.tolerations.withValue

```ts
withValue(value)
```



## obj spec.components.mixCoord.volumeMounts



### fn spec.components.mixCoord.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```



### fn spec.components.mixCoord.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```



### fn spec.components.mixCoord.volumeMounts.withName

```ts
withName(name)
```



### fn spec.components.mixCoord.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.components.mixCoord.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```



### fn spec.components.mixCoord.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```



## obj spec.components.proxy



### fn spec.components.proxy.withCommands

```ts
withCommands(commands)
```



### fn spec.components.proxy.withCommandsMixin

```ts
withCommandsMixin(commands)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.withEnv

```ts
withEnv(env)
```



### fn spec.components.proxy.withEnvMixin

```ts
withEnvMixin(env)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.withImage

```ts
withImage(image)
```



### fn spec.components.proxy.withImagePullPolicy

```ts
withImagePullPolicy(imagePullPolicy)
```



### fn spec.components.proxy.withImagePullSecrets

```ts
withImagePullSecrets(imagePullSecrets)
```



### fn spec.components.proxy.withImagePullSecretsMixin

```ts
withImagePullSecretsMixin(imagePullSecrets)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.withInitContainers

```ts
withInitContainers(initContainers)
```



### fn spec.components.proxy.withInitContainersMixin

```ts
withInitContainersMixin(initContainers)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.withNodeSelector

```ts
withNodeSelector(nodeSelector)
```



### fn spec.components.proxy.withNodeSelectorMixin

```ts
withNodeSelectorMixin(nodeSelector)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.withPaused

```ts
withPaused(paused)
```



### fn spec.components.proxy.withPodAnnotations

```ts
withPodAnnotations(podAnnotations)
```



### fn spec.components.proxy.withPodAnnotationsMixin

```ts
withPodAnnotationsMixin(podAnnotations)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.withPodLabels

```ts
withPodLabels(podLabels)
```



### fn spec.components.proxy.withPodLabelsMixin

```ts
withPodLabelsMixin(podLabels)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.withPort

```ts
withPort(port)
```



### fn spec.components.proxy.withPriorityClassName

```ts
withPriorityClassName(priorityClassName)
```



### fn spec.components.proxy.withReplicas

```ts
withReplicas(replicas)
```



### fn spec.components.proxy.withRunWithSubProcess

```ts
withRunWithSubProcess(runWithSubProcess)
```



### fn spec.components.proxy.withSchedulerName

```ts
withSchedulerName(schedulerName)
```



### fn spec.components.proxy.withServiceAccountName

```ts
withServiceAccountName(serviceAccountName)
```



### fn spec.components.proxy.withServiceAnnotations

```ts
withServiceAnnotations(serviceAnnotations)
```



### fn spec.components.proxy.withServiceAnnotationsMixin

```ts
withServiceAnnotationsMixin(serviceAnnotations)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.withServiceLabels

```ts
withServiceLabels(serviceLabels)
```



### fn spec.components.proxy.withServiceLabelsMixin

```ts
withServiceLabelsMixin(serviceLabels)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.withServiceRestfulPort

```ts
withServiceRestfulPort(serviceRestfulPort)
```



### fn spec.components.proxy.withServiceType

```ts
withServiceType(serviceType)
```



### fn spec.components.proxy.withSidecars

```ts
withSidecars(sidecars)
```



### fn spec.components.proxy.withSidecarsMixin

```ts
withSidecarsMixin(sidecars)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.withTolerations

```ts
withTolerations(tolerations)
```



### fn spec.components.proxy.withTolerationsMixin

```ts
withTolerationsMixin(tolerations)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```



### fn spec.components.proxy.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.withVolumes

```ts
withVolumes(volumes)
```



### fn spec.components.proxy.withVolumesMixin

```ts
withVolumesMixin(volumes)
```



**Note:** This function appends passed data to existing values

## obj spec.components.proxy.affinity



## obj spec.components.proxy.affinity.nodeAffinity



### fn spec.components.proxy.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.proxy.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.proxy.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.proxy.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.proxy.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference



### fn spec.components.proxy.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.proxy.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.components.proxy.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.components.proxy.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions



### fn spec.components.proxy.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.proxy.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.proxy.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.proxy.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.proxy.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields



### fn spec.components.proxy.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withKey

```ts
withKey(key)
```



### fn spec.components.proxy.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.components.proxy.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValues

```ts
withValues(values)
```



### fn spec.components.proxy.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.proxy.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.proxy.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTerms

```ts
withNodeSelectorTerms(nodeSelectorTerms)
```



### fn spec.components.proxy.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTermsMixin

```ts
withNodeSelectorTermsMixin(nodeSelectorTerms)
```



**Note:** This function appends passed data to existing values

## obj spec.components.proxy.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms



### fn spec.components.proxy.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.proxy.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.components.proxy.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.components.proxy.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions



### fn spec.components.proxy.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.proxy.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.proxy.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.proxy.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.proxy.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields



### fn spec.components.proxy.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withKey

```ts
withKey(key)
```



### fn spec.components.proxy.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.components.proxy.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValues

```ts
withValues(values)
```



### fn spec.components.proxy.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.proxy.affinity.podAffinity



### fn spec.components.proxy.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.proxy.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.proxy.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.proxy.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.proxy.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.proxy.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.proxy.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.proxy.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.components.proxy.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.proxy.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.proxy.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.proxy.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.components.proxy.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.proxy.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.proxy.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.proxy.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.proxy.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.components.proxy.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.proxy.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.proxy.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.proxy.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.components.proxy.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.proxy.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.proxy.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.proxy.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.proxy.affinity.podAntiAffinity



### fn spec.components.proxy.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.proxy.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.proxy.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.proxy.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.proxy.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.proxy.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.proxy.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.proxy.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.components.proxy.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.proxy.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.proxy.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.proxy.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.components.proxy.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.proxy.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.proxy.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.proxy.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.proxy.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.components.proxy.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.proxy.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.proxy.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.proxy.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.components.proxy.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.proxy.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.proxy.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.proxy.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.proxy.env



### fn spec.components.proxy.env.withName

```ts
withName(name)
```



### fn spec.components.proxy.env.withValue

```ts
withValue(value)
```



## obj spec.components.proxy.env.valueFrom



## obj spec.components.proxy.env.valueFrom.configMapKeyRef



### fn spec.components.proxy.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```



### fn spec.components.proxy.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```



### fn spec.components.proxy.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.components.proxy.env.valueFrom.fieldRef



### fn spec.components.proxy.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.components.proxy.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.components.proxy.env.valueFrom.resourceFieldRef



### fn spec.components.proxy.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.components.proxy.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.components.proxy.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.components.proxy.env.valueFrom.secretKeyRef



### fn spec.components.proxy.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```



### fn spec.components.proxy.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```



### fn spec.components.proxy.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.components.proxy.imagePullSecrets



### fn spec.components.proxy.imagePullSecrets.withName

```ts
withName(name)
```



## obj spec.components.proxy.ingress



### fn spec.components.proxy.ingress.withAnnotations

```ts
withAnnotations(annotations)
```



### fn spec.components.proxy.ingress.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.ingress.withHosts

```ts
withHosts(hosts)
```



### fn spec.components.proxy.ingress.withHostsMixin

```ts
withHostsMixin(hosts)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.ingress.withIngressClassName

```ts
withIngressClassName(ingressClassName)
```



### fn spec.components.proxy.ingress.withLabels

```ts
withLabels(labels)
```



### fn spec.components.proxy.ingress.withLabelsMixin

```ts
withLabelsMixin(labels)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.ingress.withTlsSecretRefs

```ts
withTlsSecretRefs(tlsSecretRefs)
```



### fn spec.components.proxy.ingress.withTlsSecretRefsMixin

```ts
withTlsSecretRefsMixin(tlsSecretRefs)
```



**Note:** This function appends passed data to existing values

## obj spec.components.proxy.resources



### fn spec.components.proxy.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.components.proxy.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.components.proxy.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.components.proxy.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.components.proxy.tolerations



### fn spec.components.proxy.tolerations.withEffect

```ts
withEffect(effect)
```



### fn spec.components.proxy.tolerations.withKey

```ts
withKey(key)
```



### fn spec.components.proxy.tolerations.withOperator

```ts
withOperator(operator)
```



### fn spec.components.proxy.tolerations.withTolerationSeconds

```ts
withTolerationSeconds(tolerationSeconds)
```



### fn spec.components.proxy.tolerations.withValue

```ts
withValue(value)
```



## obj spec.components.proxy.volumeMounts



### fn spec.components.proxy.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```



### fn spec.components.proxy.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```



### fn spec.components.proxy.volumeMounts.withName

```ts
withName(name)
```



### fn spec.components.proxy.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.components.proxy.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```



### fn spec.components.proxy.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```



## obj spec.components.queryCoord



### fn spec.components.queryCoord.withCommands

```ts
withCommands(commands)
```



### fn spec.components.queryCoord.withCommandsMixin

```ts
withCommandsMixin(commands)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryCoord.withEnv

```ts
withEnv(env)
```



### fn spec.components.queryCoord.withEnvMixin

```ts
withEnvMixin(env)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryCoord.withImage

```ts
withImage(image)
```



### fn spec.components.queryCoord.withImagePullPolicy

```ts
withImagePullPolicy(imagePullPolicy)
```



### fn spec.components.queryCoord.withImagePullSecrets

```ts
withImagePullSecrets(imagePullSecrets)
```



### fn spec.components.queryCoord.withImagePullSecretsMixin

```ts
withImagePullSecretsMixin(imagePullSecrets)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryCoord.withInitContainers

```ts
withInitContainers(initContainers)
```



### fn spec.components.queryCoord.withInitContainersMixin

```ts
withInitContainersMixin(initContainers)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryCoord.withNodeSelector

```ts
withNodeSelector(nodeSelector)
```



### fn spec.components.queryCoord.withNodeSelectorMixin

```ts
withNodeSelectorMixin(nodeSelector)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryCoord.withPaused

```ts
withPaused(paused)
```



### fn spec.components.queryCoord.withPodAnnotations

```ts
withPodAnnotations(podAnnotations)
```



### fn spec.components.queryCoord.withPodAnnotationsMixin

```ts
withPodAnnotationsMixin(podAnnotations)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryCoord.withPodLabels

```ts
withPodLabels(podLabels)
```



### fn spec.components.queryCoord.withPodLabelsMixin

```ts
withPodLabelsMixin(podLabels)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryCoord.withPort

```ts
withPort(port)
```



### fn spec.components.queryCoord.withPriorityClassName

```ts
withPriorityClassName(priorityClassName)
```



### fn spec.components.queryCoord.withReplicas

```ts
withReplicas(replicas)
```



### fn spec.components.queryCoord.withRunWithSubProcess

```ts
withRunWithSubProcess(runWithSubProcess)
```



### fn spec.components.queryCoord.withSchedulerName

```ts
withSchedulerName(schedulerName)
```



### fn spec.components.queryCoord.withServiceAccountName

```ts
withServiceAccountName(serviceAccountName)
```



### fn spec.components.queryCoord.withSidecars

```ts
withSidecars(sidecars)
```



### fn spec.components.queryCoord.withSidecarsMixin

```ts
withSidecarsMixin(sidecars)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryCoord.withTolerations

```ts
withTolerations(tolerations)
```



### fn spec.components.queryCoord.withTolerationsMixin

```ts
withTolerationsMixin(tolerations)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryCoord.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```



### fn spec.components.queryCoord.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryCoord.withVolumes

```ts
withVolumes(volumes)
```



### fn spec.components.queryCoord.withVolumesMixin

```ts
withVolumesMixin(volumes)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryCoord.affinity



## obj spec.components.queryCoord.affinity.nodeAffinity



### fn spec.components.queryCoord.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.queryCoord.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.queryCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.queryCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference



### fn spec.components.queryCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.queryCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.components.queryCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions



### fn spec.components.queryCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.queryCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.queryCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.queryCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields



### fn spec.components.queryCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withKey

```ts
withKey(key)
```



### fn spec.components.queryCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.components.queryCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValues

```ts
withValues(values)
```



### fn spec.components.queryCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.queryCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTerms

```ts
withNodeSelectorTerms(nodeSelectorTerms)
```



### fn spec.components.queryCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTermsMixin

```ts
withNodeSelectorTermsMixin(nodeSelectorTerms)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms



### fn spec.components.queryCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.queryCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.components.queryCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions



### fn spec.components.queryCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.queryCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.queryCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.queryCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields



### fn spec.components.queryCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withKey

```ts
withKey(key)
```



### fn spec.components.queryCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.components.queryCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValues

```ts
withValues(values)
```



### fn spec.components.queryCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryCoord.affinity.podAffinity



### fn spec.components.queryCoord.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.queryCoord.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryCoord.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.queryCoord.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.queryCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.queryCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.queryCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.queryCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.components.queryCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.queryCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.queryCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.components.queryCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.queryCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.queryCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.queryCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.components.queryCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.queryCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.queryCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.components.queryCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.queryCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.queryCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.queryCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryCoord.affinity.podAntiAffinity



### fn spec.components.queryCoord.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.queryCoord.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryCoord.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.queryCoord.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.queryCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.queryCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.queryCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.queryCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.components.queryCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.queryCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.queryCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.components.queryCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.queryCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.queryCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.queryCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.components.queryCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.queryCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.queryCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.components.queryCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.queryCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.queryCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.queryCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryCoord.env



### fn spec.components.queryCoord.env.withName

```ts
withName(name)
```



### fn spec.components.queryCoord.env.withValue

```ts
withValue(value)
```



## obj spec.components.queryCoord.env.valueFrom



## obj spec.components.queryCoord.env.valueFrom.configMapKeyRef



### fn spec.components.queryCoord.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```



### fn spec.components.queryCoord.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```



### fn spec.components.queryCoord.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.components.queryCoord.env.valueFrom.fieldRef



### fn spec.components.queryCoord.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.components.queryCoord.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.components.queryCoord.env.valueFrom.resourceFieldRef



### fn spec.components.queryCoord.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.components.queryCoord.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.components.queryCoord.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.components.queryCoord.env.valueFrom.secretKeyRef



### fn spec.components.queryCoord.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```



### fn spec.components.queryCoord.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```



### fn spec.components.queryCoord.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.components.queryCoord.imagePullSecrets



### fn spec.components.queryCoord.imagePullSecrets.withName

```ts
withName(name)
```



## obj spec.components.queryCoord.resources



### fn spec.components.queryCoord.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.components.queryCoord.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryCoord.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.components.queryCoord.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryCoord.tolerations



### fn spec.components.queryCoord.tolerations.withEffect

```ts
withEffect(effect)
```



### fn spec.components.queryCoord.tolerations.withKey

```ts
withKey(key)
```



### fn spec.components.queryCoord.tolerations.withOperator

```ts
withOperator(operator)
```



### fn spec.components.queryCoord.tolerations.withTolerationSeconds

```ts
withTolerationSeconds(tolerationSeconds)
```



### fn spec.components.queryCoord.tolerations.withValue

```ts
withValue(value)
```



## obj spec.components.queryCoord.volumeMounts



### fn spec.components.queryCoord.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```



### fn spec.components.queryCoord.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```



### fn spec.components.queryCoord.volumeMounts.withName

```ts
withName(name)
```



### fn spec.components.queryCoord.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.components.queryCoord.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```



### fn spec.components.queryCoord.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```



## obj spec.components.queryNode



### fn spec.components.queryNode.withCommands

```ts
withCommands(commands)
```



### fn spec.components.queryNode.withCommandsMixin

```ts
withCommandsMixin(commands)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryNode.withEnv

```ts
withEnv(env)
```



### fn spec.components.queryNode.withEnvMixin

```ts
withEnvMixin(env)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryNode.withImage

```ts
withImage(image)
```



### fn spec.components.queryNode.withImagePullPolicy

```ts
withImagePullPolicy(imagePullPolicy)
```



### fn spec.components.queryNode.withImagePullSecrets

```ts
withImagePullSecrets(imagePullSecrets)
```



### fn spec.components.queryNode.withImagePullSecretsMixin

```ts
withImagePullSecretsMixin(imagePullSecrets)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryNode.withInitContainers

```ts
withInitContainers(initContainers)
```



### fn spec.components.queryNode.withInitContainersMixin

```ts
withInitContainersMixin(initContainers)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryNode.withNodeSelector

```ts
withNodeSelector(nodeSelector)
```



### fn spec.components.queryNode.withNodeSelectorMixin

```ts
withNodeSelectorMixin(nodeSelector)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryNode.withPaused

```ts
withPaused(paused)
```



### fn spec.components.queryNode.withPodAnnotations

```ts
withPodAnnotations(podAnnotations)
```



### fn spec.components.queryNode.withPodAnnotationsMixin

```ts
withPodAnnotationsMixin(podAnnotations)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryNode.withPodLabels

```ts
withPodLabels(podLabels)
```



### fn spec.components.queryNode.withPodLabelsMixin

```ts
withPodLabelsMixin(podLabels)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryNode.withPort

```ts
withPort(port)
```



### fn spec.components.queryNode.withPriorityClassName

```ts
withPriorityClassName(priorityClassName)
```



### fn spec.components.queryNode.withReplicas

```ts
withReplicas(replicas)
```



### fn spec.components.queryNode.withRunWithSubProcess

```ts
withRunWithSubProcess(runWithSubProcess)
```



### fn spec.components.queryNode.withSchedulerName

```ts
withSchedulerName(schedulerName)
```



### fn spec.components.queryNode.withServiceAccountName

```ts
withServiceAccountName(serviceAccountName)
```



### fn spec.components.queryNode.withSidecars

```ts
withSidecars(sidecars)
```



### fn spec.components.queryNode.withSidecarsMixin

```ts
withSidecarsMixin(sidecars)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryNode.withTolerations

```ts
withTolerations(tolerations)
```



### fn spec.components.queryNode.withTolerationsMixin

```ts
withTolerationsMixin(tolerations)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryNode.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```



### fn spec.components.queryNode.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryNode.withVolumes

```ts
withVolumes(volumes)
```



### fn spec.components.queryNode.withVolumesMixin

```ts
withVolumesMixin(volumes)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryNode.affinity



## obj spec.components.queryNode.affinity.nodeAffinity



### fn spec.components.queryNode.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.queryNode.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.queryNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.queryNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference



### fn spec.components.queryNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.queryNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.components.queryNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions



### fn spec.components.queryNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.queryNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.queryNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.queryNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields



### fn spec.components.queryNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withKey

```ts
withKey(key)
```



### fn spec.components.queryNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.components.queryNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValues

```ts
withValues(values)
```



### fn spec.components.queryNode.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.queryNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTerms

```ts
withNodeSelectorTerms(nodeSelectorTerms)
```



### fn spec.components.queryNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTermsMixin

```ts
withNodeSelectorTermsMixin(nodeSelectorTerms)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms



### fn spec.components.queryNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.queryNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.components.queryNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions



### fn spec.components.queryNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.queryNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.queryNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.queryNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields



### fn spec.components.queryNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withKey

```ts
withKey(key)
```



### fn spec.components.queryNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.components.queryNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValues

```ts
withValues(values)
```



### fn spec.components.queryNode.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryNode.affinity.podAffinity



### fn spec.components.queryNode.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.queryNode.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryNode.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.queryNode.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.queryNode.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.queryNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.queryNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.queryNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.components.queryNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.queryNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.queryNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.components.queryNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.queryNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.queryNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.queryNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.components.queryNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.queryNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.queryNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.components.queryNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.queryNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.queryNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.queryNode.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryNode.affinity.podAntiAffinity



### fn spec.components.queryNode.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.queryNode.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryNode.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.queryNode.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.queryNode.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.queryNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.queryNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.queryNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.components.queryNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.queryNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.queryNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.components.queryNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.queryNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.queryNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.queryNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.components.queryNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.queryNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.queryNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.components.queryNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.queryNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.queryNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.queryNode.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryNode.env



### fn spec.components.queryNode.env.withName

```ts
withName(name)
```



### fn spec.components.queryNode.env.withValue

```ts
withValue(value)
```



## obj spec.components.queryNode.env.valueFrom



## obj spec.components.queryNode.env.valueFrom.configMapKeyRef



### fn spec.components.queryNode.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```



### fn spec.components.queryNode.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```



### fn spec.components.queryNode.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.components.queryNode.env.valueFrom.fieldRef



### fn spec.components.queryNode.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.components.queryNode.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.components.queryNode.env.valueFrom.resourceFieldRef



### fn spec.components.queryNode.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.components.queryNode.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.components.queryNode.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.components.queryNode.env.valueFrom.secretKeyRef



### fn spec.components.queryNode.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```



### fn spec.components.queryNode.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```



### fn spec.components.queryNode.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.components.queryNode.imagePullSecrets



### fn spec.components.queryNode.imagePullSecrets.withName

```ts
withName(name)
```



## obj spec.components.queryNode.resources



### fn spec.components.queryNode.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.components.queryNode.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.components.queryNode.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.components.queryNode.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.components.queryNode.tolerations



### fn spec.components.queryNode.tolerations.withEffect

```ts
withEffect(effect)
```



### fn spec.components.queryNode.tolerations.withKey

```ts
withKey(key)
```



### fn spec.components.queryNode.tolerations.withOperator

```ts
withOperator(operator)
```



### fn spec.components.queryNode.tolerations.withTolerationSeconds

```ts
withTolerationSeconds(tolerationSeconds)
```



### fn spec.components.queryNode.tolerations.withValue

```ts
withValue(value)
```



## obj spec.components.queryNode.volumeMounts



### fn spec.components.queryNode.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```



### fn spec.components.queryNode.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```



### fn spec.components.queryNode.volumeMounts.withName

```ts
withName(name)
```



### fn spec.components.queryNode.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.components.queryNode.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```



### fn spec.components.queryNode.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```



## obj spec.components.resources



### fn spec.components.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.components.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.components.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.components.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.components.rootCoord



### fn spec.components.rootCoord.withCommands

```ts
withCommands(commands)
```



### fn spec.components.rootCoord.withCommandsMixin

```ts
withCommandsMixin(commands)
```



**Note:** This function appends passed data to existing values

### fn spec.components.rootCoord.withEnv

```ts
withEnv(env)
```



### fn spec.components.rootCoord.withEnvMixin

```ts
withEnvMixin(env)
```



**Note:** This function appends passed data to existing values

### fn spec.components.rootCoord.withImage

```ts
withImage(image)
```



### fn spec.components.rootCoord.withImagePullPolicy

```ts
withImagePullPolicy(imagePullPolicy)
```



### fn spec.components.rootCoord.withImagePullSecrets

```ts
withImagePullSecrets(imagePullSecrets)
```



### fn spec.components.rootCoord.withImagePullSecretsMixin

```ts
withImagePullSecretsMixin(imagePullSecrets)
```



**Note:** This function appends passed data to existing values

### fn spec.components.rootCoord.withInitContainers

```ts
withInitContainers(initContainers)
```



### fn spec.components.rootCoord.withInitContainersMixin

```ts
withInitContainersMixin(initContainers)
```



**Note:** This function appends passed data to existing values

### fn spec.components.rootCoord.withNodeSelector

```ts
withNodeSelector(nodeSelector)
```



### fn spec.components.rootCoord.withNodeSelectorMixin

```ts
withNodeSelectorMixin(nodeSelector)
```



**Note:** This function appends passed data to existing values

### fn spec.components.rootCoord.withPaused

```ts
withPaused(paused)
```



### fn spec.components.rootCoord.withPodAnnotations

```ts
withPodAnnotations(podAnnotations)
```



### fn spec.components.rootCoord.withPodAnnotationsMixin

```ts
withPodAnnotationsMixin(podAnnotations)
```



**Note:** This function appends passed data to existing values

### fn spec.components.rootCoord.withPodLabels

```ts
withPodLabels(podLabels)
```



### fn spec.components.rootCoord.withPodLabelsMixin

```ts
withPodLabelsMixin(podLabels)
```



**Note:** This function appends passed data to existing values

### fn spec.components.rootCoord.withPort

```ts
withPort(port)
```



### fn spec.components.rootCoord.withPriorityClassName

```ts
withPriorityClassName(priorityClassName)
```



### fn spec.components.rootCoord.withReplicas

```ts
withReplicas(replicas)
```



### fn spec.components.rootCoord.withRunWithSubProcess

```ts
withRunWithSubProcess(runWithSubProcess)
```



### fn spec.components.rootCoord.withSchedulerName

```ts
withSchedulerName(schedulerName)
```



### fn spec.components.rootCoord.withServiceAccountName

```ts
withServiceAccountName(serviceAccountName)
```



### fn spec.components.rootCoord.withSidecars

```ts
withSidecars(sidecars)
```



### fn spec.components.rootCoord.withSidecarsMixin

```ts
withSidecarsMixin(sidecars)
```



**Note:** This function appends passed data to existing values

### fn spec.components.rootCoord.withTolerations

```ts
withTolerations(tolerations)
```



### fn spec.components.rootCoord.withTolerationsMixin

```ts
withTolerationsMixin(tolerations)
```



**Note:** This function appends passed data to existing values

### fn spec.components.rootCoord.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```



### fn spec.components.rootCoord.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```



**Note:** This function appends passed data to existing values

### fn spec.components.rootCoord.withVolumes

```ts
withVolumes(volumes)
```



### fn spec.components.rootCoord.withVolumesMixin

```ts
withVolumesMixin(volumes)
```



**Note:** This function appends passed data to existing values

## obj spec.components.rootCoord.affinity



## obj spec.components.rootCoord.affinity.nodeAffinity



### fn spec.components.rootCoord.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.rootCoord.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.rootCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.rootCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.rootCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference



### fn spec.components.rootCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.rootCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.rootCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.components.rootCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.components.rootCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions



### fn spec.components.rootCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.rootCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.rootCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.rootCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.rootCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields



### fn spec.components.rootCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withKey

```ts
withKey(key)
```



### fn spec.components.rootCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.components.rootCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValues

```ts
withValues(values)
```



### fn spec.components.rootCoord.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.rootCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.rootCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTerms

```ts
withNodeSelectorTerms(nodeSelectorTerms)
```



### fn spec.components.rootCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTermsMixin

```ts
withNodeSelectorTermsMixin(nodeSelectorTerms)
```



**Note:** This function appends passed data to existing values

## obj spec.components.rootCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms



### fn spec.components.rootCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.rootCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.rootCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.components.rootCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.components.rootCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions



### fn spec.components.rootCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.rootCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.rootCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.rootCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.rootCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields



### fn spec.components.rootCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withKey

```ts
withKey(key)
```



### fn spec.components.rootCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.components.rootCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValues

```ts
withValues(values)
```



### fn spec.components.rootCoord.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.rootCoord.affinity.podAffinity



### fn spec.components.rootCoord.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.rootCoord.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.components.rootCoord.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.rootCoord.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.rootCoord.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.rootCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.rootCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.rootCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.rootCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.rootCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.components.rootCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.rootCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.rootCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.rootCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.rootCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.components.rootCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.rootCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.rootCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.rootCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.rootCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.components.rootCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.rootCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.rootCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.rootCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.rootCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.components.rootCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.rootCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.rootCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.rootCoord.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.rootCoord.affinity.podAntiAffinity



### fn spec.components.rootCoord.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.rootCoord.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.components.rootCoord.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.rootCoord.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.rootCoord.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.rootCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.rootCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.rootCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.rootCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.rootCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.components.rootCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.rootCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.rootCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.rootCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.rootCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.components.rootCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.rootCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.rootCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.rootCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.rootCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.components.rootCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.rootCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.rootCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.rootCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.rootCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.components.rootCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.rootCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.rootCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.rootCoord.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.rootCoord.env



### fn spec.components.rootCoord.env.withName

```ts
withName(name)
```



### fn spec.components.rootCoord.env.withValue

```ts
withValue(value)
```



## obj spec.components.rootCoord.env.valueFrom



## obj spec.components.rootCoord.env.valueFrom.configMapKeyRef



### fn spec.components.rootCoord.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```



### fn spec.components.rootCoord.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```



### fn spec.components.rootCoord.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.components.rootCoord.env.valueFrom.fieldRef



### fn spec.components.rootCoord.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.components.rootCoord.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.components.rootCoord.env.valueFrom.resourceFieldRef



### fn spec.components.rootCoord.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.components.rootCoord.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.components.rootCoord.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.components.rootCoord.env.valueFrom.secretKeyRef



### fn spec.components.rootCoord.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```



### fn spec.components.rootCoord.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```



### fn spec.components.rootCoord.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.components.rootCoord.imagePullSecrets



### fn spec.components.rootCoord.imagePullSecrets.withName

```ts
withName(name)
```



## obj spec.components.rootCoord.resources



### fn spec.components.rootCoord.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.components.rootCoord.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.components.rootCoord.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.components.rootCoord.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.components.rootCoord.tolerations



### fn spec.components.rootCoord.tolerations.withEffect

```ts
withEffect(effect)
```



### fn spec.components.rootCoord.tolerations.withKey

```ts
withKey(key)
```



### fn spec.components.rootCoord.tolerations.withOperator

```ts
withOperator(operator)
```



### fn spec.components.rootCoord.tolerations.withTolerationSeconds

```ts
withTolerationSeconds(tolerationSeconds)
```



### fn spec.components.rootCoord.tolerations.withValue

```ts
withValue(value)
```



## obj spec.components.rootCoord.volumeMounts



### fn spec.components.rootCoord.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```



### fn spec.components.rootCoord.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```



### fn spec.components.rootCoord.volumeMounts.withName

```ts
withName(name)
```



### fn spec.components.rootCoord.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.components.rootCoord.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```



### fn spec.components.rootCoord.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```



## obj spec.components.standalone



### fn spec.components.standalone.withCommands

```ts
withCommands(commands)
```



### fn spec.components.standalone.withCommandsMixin

```ts
withCommandsMixin(commands)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.withEnv

```ts
withEnv(env)
```



### fn spec.components.standalone.withEnvMixin

```ts
withEnvMixin(env)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.withImage

```ts
withImage(image)
```



### fn spec.components.standalone.withImagePullPolicy

```ts
withImagePullPolicy(imagePullPolicy)
```



### fn spec.components.standalone.withImagePullSecrets

```ts
withImagePullSecrets(imagePullSecrets)
```



### fn spec.components.standalone.withImagePullSecretsMixin

```ts
withImagePullSecretsMixin(imagePullSecrets)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.withInitContainers

```ts
withInitContainers(initContainers)
```



### fn spec.components.standalone.withInitContainersMixin

```ts
withInitContainersMixin(initContainers)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.withNodeSelector

```ts
withNodeSelector(nodeSelector)
```



### fn spec.components.standalone.withNodeSelectorMixin

```ts
withNodeSelectorMixin(nodeSelector)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.withPaused

```ts
withPaused(paused)
```



### fn spec.components.standalone.withPodAnnotations

```ts
withPodAnnotations(podAnnotations)
```



### fn spec.components.standalone.withPodAnnotationsMixin

```ts
withPodAnnotationsMixin(podAnnotations)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.withPodLabels

```ts
withPodLabels(podLabels)
```



### fn spec.components.standalone.withPodLabelsMixin

```ts
withPodLabelsMixin(podLabels)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.withPort

```ts
withPort(port)
```



### fn spec.components.standalone.withPriorityClassName

```ts
withPriorityClassName(priorityClassName)
```



### fn spec.components.standalone.withReplicas

```ts
withReplicas(replicas)
```



### fn spec.components.standalone.withRunWithSubProcess

```ts
withRunWithSubProcess(runWithSubProcess)
```



### fn spec.components.standalone.withSchedulerName

```ts
withSchedulerName(schedulerName)
```



### fn spec.components.standalone.withServiceAccountName

```ts
withServiceAccountName(serviceAccountName)
```



### fn spec.components.standalone.withServiceAnnotations

```ts
withServiceAnnotations(serviceAnnotations)
```



### fn spec.components.standalone.withServiceAnnotationsMixin

```ts
withServiceAnnotationsMixin(serviceAnnotations)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.withServiceLabels

```ts
withServiceLabels(serviceLabels)
```



### fn spec.components.standalone.withServiceLabelsMixin

```ts
withServiceLabelsMixin(serviceLabels)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.withServiceRestfulPort

```ts
withServiceRestfulPort(serviceRestfulPort)
```



### fn spec.components.standalone.withServiceType

```ts
withServiceType(serviceType)
```



### fn spec.components.standalone.withSidecars

```ts
withSidecars(sidecars)
```



### fn spec.components.standalone.withSidecarsMixin

```ts
withSidecarsMixin(sidecars)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.withTolerations

```ts
withTolerations(tolerations)
```



### fn spec.components.standalone.withTolerationsMixin

```ts
withTolerationsMixin(tolerations)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```



### fn spec.components.standalone.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.withVolumes

```ts
withVolumes(volumes)
```



### fn spec.components.standalone.withVolumesMixin

```ts
withVolumesMixin(volumes)
```



**Note:** This function appends passed data to existing values

## obj spec.components.standalone.affinity



## obj spec.components.standalone.affinity.nodeAffinity



### fn spec.components.standalone.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.standalone.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.standalone.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.standalone.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.standalone.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference



### fn spec.components.standalone.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.standalone.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.components.standalone.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.components.standalone.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions



### fn spec.components.standalone.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.standalone.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.standalone.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.standalone.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.standalone.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields



### fn spec.components.standalone.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withKey

```ts
withKey(key)
```



### fn spec.components.standalone.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.components.standalone.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValues

```ts
withValues(values)
```



### fn spec.components.standalone.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.standalone.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.standalone.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTerms

```ts
withNodeSelectorTerms(nodeSelectorTerms)
```



### fn spec.components.standalone.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTermsMixin

```ts
withNodeSelectorTermsMixin(nodeSelectorTerms)
```



**Note:** This function appends passed data to existing values

## obj spec.components.standalone.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms



### fn spec.components.standalone.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.standalone.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.components.standalone.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.components.standalone.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions



### fn spec.components.standalone.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.standalone.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.standalone.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.standalone.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.standalone.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields



### fn spec.components.standalone.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withKey

```ts
withKey(key)
```



### fn spec.components.standalone.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.components.standalone.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValues

```ts
withValues(values)
```



### fn spec.components.standalone.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.standalone.affinity.podAffinity



### fn spec.components.standalone.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.standalone.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.standalone.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.standalone.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.standalone.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.standalone.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.standalone.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.standalone.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.components.standalone.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.standalone.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.standalone.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.standalone.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.components.standalone.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.standalone.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.standalone.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.standalone.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.standalone.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.components.standalone.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.standalone.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.standalone.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.standalone.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.components.standalone.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.standalone.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.standalone.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.standalone.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.standalone.affinity.podAntiAffinity



### fn spec.components.standalone.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.standalone.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.components.standalone.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.standalone.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.standalone.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.components.standalone.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.components.standalone.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.components.standalone.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.components.standalone.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.standalone.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.standalone.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.standalone.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.components.standalone.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.standalone.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.standalone.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.standalone.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.standalone.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.components.standalone.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.components.standalone.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.components.standalone.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.components.standalone.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.components.standalone.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.components.standalone.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.components.standalone.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.components.standalone.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.components.standalone.env



### fn spec.components.standalone.env.withName

```ts
withName(name)
```



### fn spec.components.standalone.env.withValue

```ts
withValue(value)
```



## obj spec.components.standalone.env.valueFrom



## obj spec.components.standalone.env.valueFrom.configMapKeyRef



### fn spec.components.standalone.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```



### fn spec.components.standalone.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```



### fn spec.components.standalone.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.components.standalone.env.valueFrom.fieldRef



### fn spec.components.standalone.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.components.standalone.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.components.standalone.env.valueFrom.resourceFieldRef



### fn spec.components.standalone.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.components.standalone.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.components.standalone.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.components.standalone.env.valueFrom.secretKeyRef



### fn spec.components.standalone.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```



### fn spec.components.standalone.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```



### fn spec.components.standalone.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.components.standalone.imagePullSecrets



### fn spec.components.standalone.imagePullSecrets.withName

```ts
withName(name)
```



## obj spec.components.standalone.ingress



### fn spec.components.standalone.ingress.withAnnotations

```ts
withAnnotations(annotations)
```



### fn spec.components.standalone.ingress.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.ingress.withHosts

```ts
withHosts(hosts)
```



### fn spec.components.standalone.ingress.withHostsMixin

```ts
withHostsMixin(hosts)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.ingress.withIngressClassName

```ts
withIngressClassName(ingressClassName)
```



### fn spec.components.standalone.ingress.withLabels

```ts
withLabels(labels)
```



### fn spec.components.standalone.ingress.withLabelsMixin

```ts
withLabelsMixin(labels)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.ingress.withTlsSecretRefs

```ts
withTlsSecretRefs(tlsSecretRefs)
```



### fn spec.components.standalone.ingress.withTlsSecretRefsMixin

```ts
withTlsSecretRefsMixin(tlsSecretRefs)
```



**Note:** This function appends passed data to existing values

## obj spec.components.standalone.resources



### fn spec.components.standalone.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.components.standalone.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.components.standalone.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.components.standalone.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.components.standalone.tolerations



### fn spec.components.standalone.tolerations.withEffect

```ts
withEffect(effect)
```



### fn spec.components.standalone.tolerations.withKey

```ts
withKey(key)
```



### fn spec.components.standalone.tolerations.withOperator

```ts
withOperator(operator)
```



### fn spec.components.standalone.tolerations.withTolerationSeconds

```ts
withTolerationSeconds(tolerationSeconds)
```



### fn spec.components.standalone.tolerations.withValue

```ts
withValue(value)
```



## obj spec.components.standalone.volumeMounts



### fn spec.components.standalone.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```



### fn spec.components.standalone.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```



### fn spec.components.standalone.volumeMounts.withName

```ts
withName(name)
```



### fn spec.components.standalone.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.components.standalone.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```



### fn spec.components.standalone.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```



## obj spec.components.tolerations



### fn spec.components.tolerations.withEffect

```ts
withEffect(effect)
```



### fn spec.components.tolerations.withKey

```ts
withKey(key)
```



### fn spec.components.tolerations.withOperator

```ts
withOperator(operator)
```



### fn spec.components.tolerations.withTolerationSeconds

```ts
withTolerationSeconds(tolerationSeconds)
```



### fn spec.components.tolerations.withValue

```ts
withValue(value)
```



## obj spec.components.volumeMounts



### fn spec.components.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```



### fn spec.components.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```



### fn spec.components.volumeMounts.withName

```ts
withName(name)
```



### fn spec.components.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.components.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```



### fn spec.components.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```



## obj spec.dependencies



### fn spec.dependencies.withCustomMsgStream

```ts
withCustomMsgStream(customMsgStream)
```



### fn spec.dependencies.withCustomMsgStreamMixin

```ts
withCustomMsgStreamMixin(customMsgStream)
```



**Note:** This function appends passed data to existing values

### fn spec.dependencies.withMsgStreamType

```ts
withMsgStreamType(msgStreamType)
```



## obj spec.dependencies.etcd



### fn spec.dependencies.etcd.withEndpoints

```ts
withEndpoints(endpoints)
```



### fn spec.dependencies.etcd.withEndpointsMixin

```ts
withEndpointsMixin(endpoints)
```



**Note:** This function appends passed data to existing values

### fn spec.dependencies.etcd.withExternal

```ts
withExternal(external)
```



## obj spec.dependencies.etcd.inCluster



### fn spec.dependencies.etcd.inCluster.withDeletionPolicy

```ts
withDeletionPolicy(deletionPolicy)
```



### fn spec.dependencies.etcd.inCluster.withPvcDeletion

```ts
withPvcDeletion(pvcDeletion)
```



### fn spec.dependencies.etcd.inCluster.withValues

```ts
withValues(values)
```



### fn spec.dependencies.etcd.inCluster.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.dependencies.kafka



### fn spec.dependencies.kafka.withBrokerList

```ts
withBrokerList(brokerList)
```



### fn spec.dependencies.kafka.withBrokerListMixin

```ts
withBrokerListMixin(brokerList)
```



**Note:** This function appends passed data to existing values

### fn spec.dependencies.kafka.withExternal

```ts
withExternal(external)
```



## obj spec.dependencies.kafka.inCluster



### fn spec.dependencies.kafka.inCluster.withDeletionPolicy

```ts
withDeletionPolicy(deletionPolicy)
```



### fn spec.dependencies.kafka.inCluster.withPvcDeletion

```ts
withPvcDeletion(pvcDeletion)
```



### fn spec.dependencies.kafka.inCluster.withValues

```ts
withValues(values)
```



### fn spec.dependencies.kafka.inCluster.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.dependencies.natsmq



## obj spec.dependencies.natsmq.persistence



### fn spec.dependencies.natsmq.persistence.withEnabled

```ts
withEnabled(enabled)
```



### fn spec.dependencies.natsmq.persistence.withPvcDeletion

```ts
withPvcDeletion(pvcDeletion)
```



## obj spec.dependencies.natsmq.persistence.persistentVolumeClaim



### fn spec.dependencies.natsmq.persistence.persistentVolumeClaim.withAnnotations

```ts
withAnnotations(annotations)
```



### fn spec.dependencies.natsmq.persistence.persistentVolumeClaim.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```



**Note:** This function appends passed data to existing values

### fn spec.dependencies.natsmq.persistence.persistentVolumeClaim.withExistingClaim

```ts
withExistingClaim(existingClaim)
```



### fn spec.dependencies.natsmq.persistence.persistentVolumeClaim.withLabels

```ts
withLabels(labels)
```



### fn spec.dependencies.natsmq.persistence.persistentVolumeClaim.withLabelsMixin

```ts
withLabelsMixin(labels)
```



**Note:** This function appends passed data to existing values

### fn spec.dependencies.natsmq.persistence.persistentVolumeClaim.withSpec

```ts
withSpec(spec)
```



### fn spec.dependencies.natsmq.persistence.persistentVolumeClaim.withSpecMixin

```ts
withSpecMixin(spec)
```



**Note:** This function appends passed data to existing values

## obj spec.dependencies.pulsar



### fn spec.dependencies.pulsar.withEndpoint

```ts
withEndpoint(endpoint)
```



### fn spec.dependencies.pulsar.withExternal

```ts
withExternal(external)
```



## obj spec.dependencies.pulsar.inCluster



### fn spec.dependencies.pulsar.inCluster.withDeletionPolicy

```ts
withDeletionPolicy(deletionPolicy)
```



### fn spec.dependencies.pulsar.inCluster.withPvcDeletion

```ts
withPvcDeletion(pvcDeletion)
```



### fn spec.dependencies.pulsar.inCluster.withValues

```ts
withValues(values)
```



### fn spec.dependencies.pulsar.inCluster.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.dependencies.rocksmq



## obj spec.dependencies.rocksmq.persistence



### fn spec.dependencies.rocksmq.persistence.withEnabled

```ts
withEnabled(enabled)
```



### fn spec.dependencies.rocksmq.persistence.withPvcDeletion

```ts
withPvcDeletion(pvcDeletion)
```



## obj spec.dependencies.rocksmq.persistence.persistentVolumeClaim



### fn spec.dependencies.rocksmq.persistence.persistentVolumeClaim.withAnnotations

```ts
withAnnotations(annotations)
```



### fn spec.dependencies.rocksmq.persistence.persistentVolumeClaim.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```



**Note:** This function appends passed data to existing values

### fn spec.dependencies.rocksmq.persistence.persistentVolumeClaim.withExistingClaim

```ts
withExistingClaim(existingClaim)
```



### fn spec.dependencies.rocksmq.persistence.persistentVolumeClaim.withLabels

```ts
withLabels(labels)
```



### fn spec.dependencies.rocksmq.persistence.persistentVolumeClaim.withLabelsMixin

```ts
withLabelsMixin(labels)
```



**Note:** This function appends passed data to existing values

### fn spec.dependencies.rocksmq.persistence.persistentVolumeClaim.withSpec

```ts
withSpec(spec)
```



### fn spec.dependencies.rocksmq.persistence.persistentVolumeClaim.withSpecMixin

```ts
withSpecMixin(spec)
```



**Note:** This function appends passed data to existing values

## obj spec.dependencies.storage



### fn spec.dependencies.storage.withEndpoint

```ts
withEndpoint(endpoint)
```



### fn spec.dependencies.storage.withExternal

```ts
withExternal(external)
```



### fn spec.dependencies.storage.withSecretRef

```ts
withSecretRef(secretRef)
```



### fn spec.dependencies.storage.withType

```ts
withType(type)
```



## obj spec.dependencies.storage.inCluster



### fn spec.dependencies.storage.inCluster.withDeletionPolicy

```ts
withDeletionPolicy(deletionPolicy)
```



### fn spec.dependencies.storage.inCluster.withPvcDeletion

```ts
withPvcDeletion(pvcDeletion)
```



### fn spec.dependencies.storage.inCluster.withValues

```ts
withValues(values)
```



### fn spec.dependencies.storage.inCluster.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values