.. _numetadata:

numetadata
===========================================

.. class:: numetadata.NUMetadata(bambou.nurest_object.NUMetaRESTObject,):

Metadata associated to a entity.


Attributes
----------


- ``name``: name of the Metadata.

- ``description``: Description of the Metadata.

- ``metadata_tag_ids``: metadata tag IDs associated with this metadata you can filter metadata based on this attribute for example  X-Nuage-Filter: '2d6fb627-603b-421c-b63a-eb0a6d712761' IN metadataTagIDs 

- ``network_notification_disabled``: specifies metadata changes need to be notified to controller,by default it is notified

- ``blob`` (**Mandatory**): Metadata that describes about the entity attached to it.

- ``global_metadata``: specifies metadata is global or local

- ``entity_scope``: Specify if scope of entity is Data center or Enterprise level

- ``external_id``: External object ID. Used for integration with third party systems




Children
--------

================================================================================================================================================               ==========================================================================================
**class**                                                                                                                                                      **fetcher**

:ref:`nueventlog.NUEventLog<nueventlog>`                                                                                                                         ``event_logs`` 
================================================================================================================================================               ==========================================================================================



Parents
--------


- :ref:`nucontainerinterface.NUContainerInterface<nucontainerinterface>`

- :ref:`nugroupkeyencryptionprofile.NUGroupKeyEncryptionProfile<nugroupkeyencryptionprofile>`

- :ref:`nuqos.NUQOS<nuqos>`

- :ref:`nuinfrastructureaccessprofile.NUInfrastructureAccessProfile<nuinfrastructureaccessprofile>`

- :ref:`nubgppeer.NUBGPPeer<nubgppeer>`

- :ref:`nusharednetworkresource.NUSharedNetworkResource<nusharednetworkresource>`

- :ref:`nuvirtualip.NUVirtualIP<nuvirtualip>`

- :ref:`nudscpforwardingclasstable.NUDSCPForwardingClassTable<nudscpforwardingclasstable>`

- :ref:`numulticastchannelmap.NUMultiCastChannelMap<numulticastchannelmap>`

- :ref:`nuredundancygroup.NURedundancyGroup<nuredundancygroup>`

- :ref:`nutca.NUTCA<nutca>`

- :ref:`nugroup.NUGroup<nugroup>`

- :ref:`nuvsgredundantport.NUVsgRedundantPort<nuvsgredundantport>`

- :ref:`nuzone.NUZone<nuzone>`

- :ref:`nuikegatewayprofile.NUIKEGatewayProfile<nuikegatewayprofile>`

- :ref:`nuikesubnet.NUIKESubnet<nuikesubnet>`

- :ref:`nuinfrastructuregatewayprofile.NUInfrastructureGatewayProfile<nuinfrastructuregatewayprofile>`

- :ref:`nuflowsecuritypolicy.NUFlowSecurityPolicy<nuflowsecuritypolicy>`

- :ref:`nuvcentereamconfig.NUVCenterEAMConfig<nuvcentereamconfig>`

- :ref:`nulocation.NULocation<nulocation>`

- :ref:`nuenterprisesecurity.NUEnterpriseSecurity<nuenterprisesecurity>`

- :ref:`nuvcentervrsconfig.NUVCenterVRSConfig<nuvcentervrsconfig>`

- :ref:`nuenterprisenetwork.NUEnterpriseNetwork<nuenterprisenetwork>`

- :ref:`nuinfrastructurevscprofile.NUInfrastructureVscProfile<nuinfrastructurevscprofile>`

- :ref:`nupermission.NUPermission<nupermission>`

- :ref:`nuipreservation.NUIPReservation<nuipreservation>`

- :ref:`nuredirectiontargettemplate.NURedirectionTargetTemplate<nuredirectiontargettemplate>`

- :ref:`nusubnettemplate.NUSubnetTemplate<nusubnettemplate>`

- :ref:`nufloatingipacltemplate.NUFloatingIPACLTemplate<nufloatingipacltemplate>`

- :ref:`nuikegatewayconnection.NUIKEGatewayConnection<nuikegatewayconnection>`

- :ref:`nuredirectiontarget.NURedirectionTarget<nuredirectiontarget>`

- :ref:`nuegressaclentrytemplate.NUEgressACLEntryTemplate<nuegressaclentrytemplate>`

- :ref:`nuingressexternalservicetemplateentry.NUIngressExternalServiceTemplateEntry<nuingressexternalservicetemplateentry>`

- :ref:`nuavatar.NUAvatar<nuavatar>`

- :ref:`nubootstrapactivation.NUBootstrapActivation<nubootstrapactivation>`

- :ref:`nupatnatpool.NUPATNATPool<nupatnatpool>`

- :ref:`nuvsp.NUVSP<nuvsp>`

- :ref:`nudomain.NUDomain<nudomain>`

- :ref:`nuredundantport.NURedundantPort<nuredundantport>`

- :ref:`nudscpforwardingclassmapping.NUDSCPForwardingClassMapping<nudscpforwardingclassmapping>`

- :ref:`nusystemconfig.NUSystemConfig<nusystemconfig>`

- :ref:`nuvsc.NUVSC<nuvsc>`

- :ref:`nuvport.NUVPort<nuvport>`

- :ref:`nuflowforwardingpolicy.NUFlowForwardingPolicy<nuflowforwardingpolicy>`

- :ref:`nuport.NUPort<nuport>`

- :ref:`nustatisticspolicy.NUStatisticsPolicy<nustatisticspolicy>`

- :ref:`nusubnet.NUSubnet<nusubnet>`

- :ref:`nupolicygroup.NUPolicyGroup<nupolicygroup>`

- :ref:`nuratelimiter.NURateLimiter<nuratelimiter>`

- :ref:`nukeyservermonitorencryptedseed.NUKeyServerMonitorEncryptedSeed<nukeyservermonitorencryptedseed>`

- :ref:`nuzonetemplate.NUZoneTemplate<nuzonetemplate>`

- :ref:`nukeyservermonitorseed.NUKeyServerMonitorSeed<nukeyservermonitorseed>`

- :ref:`nugatewaytemplate.NUGatewayTemplate<nugatewaytemplate>`

- :ref:`nuvrs.NUVRS<nuvrs>`

- :ref:`nuhsc.NUHSC<nuhsc>`

- :ref:`nuvlan.NUVLAN<nuvlan>`

- :ref:`nuldapconfiguration.NULDAPConfiguration<nuldapconfiguration>`

- :ref:`nuvsdcomponent.NUVSDComponent<nuvsdcomponent>`

- :ref:`nuzfbrequest.NUZFBRequest<nuzfbrequest>`

- :ref:`nuenterprisepermission.NUEnterprisePermission<nuenterprisepermission>`

- :ref:`nustaticroute.NUStaticRoute<nustaticroute>`

- :ref:`nujob.NUJob<nujob>`

- :ref:`nuvminterface.NUVMInterface<nuvminterface>`

- :ref:`nugatewaysecureddata.NUGatewaySecuredData<nugatewaysecureddata>`

- :ref:`nukeyservermonitor.NUKeyServerMonitor<nukeyservermonitor>`

- :ref:`nunetworklayout.NUNetworkLayout<nunetworklayout>`

- :ref:`nuwanservice.NUWANService<nuwanservice>`

- :ref:`nulicense.NULicense<nulicense>`

- :ref:`nuenterpriseprofile.NUEnterpriseProfile<nuenterpriseprofile>`

- :ref:`nufloatingipacltemplateentry.NUFloatingIPACLTemplateEntry<nufloatingipacltemplateentry>`

- :ref:`nubridgeinterface.NUBridgeInterface<nubridgeinterface>`

- :ref:`nuvcentercluster.NUVCenterCluster<nuvcentercluster>`

- :ref:`numulticastrange.NUMultiCastRange<numulticastrange>`

- :ref:`nunetworkmacrogroup.NUNetworkMacroGroup<nunetworkmacrogroup>`

- :ref:`nuingressadvfwdentrytemplate.NUIngressAdvFwdEntryTemplate<nuingressadvfwdentrytemplate>`

- :ref:`numulticastlist.NUMultiCastList<numulticastlist>`

- :ref:`nuautodiscoveredgateway.NUAutoDiscoveredGateway<nuautodiscoveredgateway>`

- :ref:`nunexthop.NUNextHop<nunexthop>`

- :ref:`nukeyservernotification.NUKeyServerNotification<nukeyservernotification>`

- :ref:`numirrordestination.NUMirrorDestination<numirrordestination>`

- :ref:`nunatmapentry.NUNATMapEntry<nunatmapentry>`

- :ref:`nudomainfipacltemplate.NUDomainFIPAclTemplate<nudomainfipacltemplate>`

- :ref:`nuaddressmap.NUAddressMap<nuaddressmap>`

- :ref:`nugateway.NUGateway<nugateway>`

- :ref:`numultinicvport.NUMultiNICVPort<numultinicvport>`

- :ref:`nustatistics.NUStatistics<nustatistics>`

- :ref:`nunsporttemplate.NUNSPortTemplate<nunsporttemplate>`

- :ref:`nueventlog.NUEventLog<nueventlog>`

- :ref:`nuvcenterdatacenter.NUVCenterDataCenter<nuvcenterdatacenter>`

- :ref:`nultestatistics.NULtestatistics<nultestatistics>`

- :ref:`nudomainfipacltemplateentry.NUDomainFIPAclTemplateEntry<nudomainfipacltemplateentry>`

- :ref:`nuapplicationservice.NUApplicationService<nuapplicationservice>`

- :ref:`nuikegateway.NUIKEGateway<nuikegateway>`

- :ref:`nustatscollectorinfo.NUStatsCollectorInfo<nustatscollectorinfo>`

- :ref:`nuvcenter.NUVCenter<nuvcenter>`

- :ref:`nubulkstatistics.NUBulkStatistics<nubulkstatistics>`

- :ref:`nuingressaclentrytemplate.NUIngressACLEntryTemplate<nuingressaclentrytemplate>`

- :ref:`nuroutingpolicy.NURoutingPolicy<nuroutingpolicy>`

- :ref:`nucertificate.NUCertificate<nucertificate>`

- :ref:`nul2domain.NUL2Domain<nul2domain>`

- :ref:`nuikegatewayconfig.NUIKEGatewayConfig<nuikegatewayconfig>`

- :ref:`nuhostinterface.NUHostInterface<nuhostinterface>`

- :ref:`nusiteinfo.NUSiteInfo<nusiteinfo>`

- :ref:`nulink.NULink<nulink>`

- :ref:`nuingressexternalservicetemplate.NUIngressExternalServiceTemplate<nuingressexternalservicetemplate>`

- :ref:`nuporttemplate.NUPortTemplate<nuporttemplate>`

- :ref:`nume.NUMe<nume>`

- :ref:`nudhcpoption.NUDHCPOption<nudhcpoption>`

- :ref:`nukeyservermember.NUKeyServerMember<nukeyservermember>`

- :ref:`nunsgateway.NUNSGateway<nunsgateway>`

- :ref:`nunsgatewaytemplate.NUNSGatewayTemplate<nunsgatewaytemplate>`

- :ref:`nuuplinkrd.NUUplinkRD<nuuplinkrd>`

- :ref:`nuvsd.NUVSD<nuvsd>`

- :ref:`nunsport.NUNSPort<nunsport>`

- :ref:`nuvrsaddressrange.NUVRSAddressRange<nuvrsaddressrange>`

- :ref:`nubgpprofile.NUBGPProfile<nubgpprofile>`

- :ref:`nuegressqospolicy.NUEgressQOSPolicy<nuegressqospolicy>`

- :ref:`nupublicnetworkmacro.NUPublicNetworkMacro<nupublicnetworkmacro>`

- :ref:`nul2domaintemplate.NUL2DomainTemplate<nul2domaintemplate>`

- :ref:`nuaddressrange.NUAddressRange<nuaddressrange>`

- :ref:`nudomaintemplate.NUDomainTemplate<nudomaintemplate>`

- :ref:`nuvm.NUVM<nuvm>`

- :ref:`nucloudmgmtsystem.NUCloudMgmtSystem<nucloudmgmtsystem>`

- :ref:`nuvmresync.NUVMResync<nuvmresync>`

- :ref:`nupolicydecision.NUPolicyDecision<nupolicydecision>`

- :ref:`nufloatingip.NUFloatingIp<nufloatingip>`

- :ref:`nuegressacltemplate.NUEgressACLTemplate<nuegressacltemplate>`

- :ref:`numonitoringport.NUMonitoringPort<numonitoringport>`

- :ref:`nuvpnconnection.NUVPNConnection<nuvpnconnection>`

- :ref:`nunsredundantgatewaygroup.NUNSRedundantGatewayGroup<nunsredundantgatewaygroup>`

- :ref:`nukeyservermonitorsek.NUKeyServerMonitorSEK<nukeyservermonitorsek>`

- :ref:`nuingressadvfwdtemplate.NUIngressAdvFwdTemplate<nuingressadvfwdtemplate>`

- :ref:`nuvportmirror.NUVPortMirror<nuvportmirror>`

- :ref:`nubgpneighbor.NUBGPNeighbor<nubgpneighbor>`

- :ref:`nucontainerresync.NUContainerResync<nucontainerresync>`

- :ref:`nuallalarm.NUAllAlarm<nuallalarm>`

- :ref:`nuikepsk.NUIKEPSK<nuikepsk>`

- :ref:`nuikeencryptionprofile.NUIKEEncryptionprofile<nuikeencryptionprofile>`

- :ref:`nupolicygrouptemplate.NUPolicyGroupTemplate<nupolicygrouptemplate>`

- :ref:`nuinfrastructureconfig.NUInfrastructureConfig<nuinfrastructureconfig>`

- :ref:`nuuser.NUUser<nuuser>`

- :ref:`nutier.NUTier<nutier>`

- :ref:`nucontainer.NUContainer<nucontainer>`

- :ref:`nuenterprisesecureddata.NUEnterpriseSecuredData<nuenterprisesecureddata>`

- :ref:`nualarm.NUAlarm<nualarm>`

- :ref:`nubootstrap.NUBootstrap<nubootstrap>`

- :ref:`nuflow.NUFlow<nuflow>`

- :ref:`nuvlantemplate.NUVLANTemplate<nuvlantemplate>`

- :ref:`nugatewaysecurity.NUGatewaySecurity<nugatewaysecurity>`

- :ref:`nuglobalmetadata.NUGlobalMetadata<nuglobalmetadata>`

- :ref:`nuenterprise.NUEnterprise<nuenterprise>`

- :ref:`nuikecertificate.NUIKECertificate<nuikecertificate>`

- :ref:`nuingressacltemplate.NUIngressACLTemplate<nuingressacltemplate>`

- :ref:`nuvcenterhypervisor.NUVCenterHypervisor<nuvcenterhypervisor>`
