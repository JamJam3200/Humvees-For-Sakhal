# Humvees-For-Sakhal


Are you having trouble with sliding cars around bends? are you struggling to get uphill on Sakhal?, Are you tired of frozen canteens?,  Fear not for i have the solution you are looking for!. Introducing the all new 4x4 all terrain US Army Issued Humvee's, Airdropped for your convenience. (Disclaimer, not actually air dropped just spawned in) 

This will be a rather easy install, 

The below entry for the events.xml file will need to be copied and then pasted within your own events.xml file. I’d recommend trying to locate the entry first before copying and pasting, you can do this by hitting ctrl f on your keyboard this should bring up a search bar, just put this line into the search bar :<event name="VehicleOffroad02"> and push enter, if it is unable to be located don’t stress just paste the entry below into your events.xml.  (top of the file is preferred but entirely up to you)

     <event name="VehicleOffroad02">
        <nominal>20</nominal>
        <min>8</min>
        <max>12</max>
        <lifetime>300</lifetime>
        <restock>0</restock>
        <saferadius>500</saferadius>
        <distanceradius>500</distanceradius>
        <cleanupradius>200</cleanupradius>
        <flags deletable="0" init_random="0" remove_damaged="1"/>
        <position>fixed</position>
        <limit>mixed</limit>
        <active>1</active>
        <children>
            <child lootmax="0" lootmin="0" max="12" min="8" type="Offroad_02"/>
        </children>
    </event>

     <event name="VehicleOffroad02">
        <nominal>20</nominal>
        <min>8</min>
        <max>12</max>
        <lifetime>300</lifetime>
        <restock>0</restock>
        <saferadius>500</saferadius>
        <distanceradius>500</distanceradius>
        <cleanupradius>200</cleanupradius>
        <flags deletable="0" init_random="0" remove_damaged="1"/>
        <position>fixed</position>
        <limit>mixed</limit>
        <active>0</active>
        <children>
            <child lootmax="0" lootmin="0" max="12" min="8" type="Offroad_02"/>
        </children>
    </event>



These positions will need to be placed within our Cfgeventspawns.xml, (top of the file is preferred but entirely up to you). 
They have been categorized for our convenience as you may want to adjust or remove one of the positions if needed be, this will make it easier if you intend to add your own. 

	     <event name="VehicleOffroad02">
				        <pos x="6974.190429" z="7140.311035"/>
                <pos x="7026.977050" z="7639.657714"/>
                <pos x="7304.903320" z="7260.874511"/>
                <pos x="4420.831542" z="8864.310546"/>
                <pos x="5452.690429" z="10175.280273"/>
                <pos x="7511.534179" z="9695.983398"/> 
			        	<pos x="8114.315917" z="11958.385742"/>
                <pos x="12138.188476" z="9770.791015"/>
                <pos x="10423.440429" z="8599.865234"/>
                <pos x="10282.294921" z="8573.929687"/>
                <pos x="5481.371093" z="3978.304687"/>
                <pos x="5399.75222"  z="4597.859863"/>
                <pos x="4711.471191" z="4194.943359"/>
                <pos x="5084.900878" z="4799.237304"/> 
                <pos x="3371.605468" z="6712.919921"/>  
                <pos x="3338.510742" z="6975.811523"/>
                <pos x="2908.694335" z="7007.018066"/>
                <pos x="1959.981689" z="6116.873046"/>
                <pos x="2043.789794" z="6995.459960"/>
                <pos x="964.606079"  z="7717.763671"/>
                <pos x="2518.240234" z="8726.726562"/>
                <pos x="3647.762451" z="9361.019531"/>
				        <pos x="2656.389160" z="9220.610351"/>
	        	</event>         



Once that is completed, save the changes and restart your server. (Unless you plan on doing some tweaking to the <min> and <max> to your heart's content) I would recommend increasing the nominal if you plan on tweaking how many crash sites will spawn at one time. 

If the crash sites haven’t worked (They should), I would set your <active>1</active> to <active>0</active>. Make sure you stop the server first, save changes then restart, once the server has restarted stop the server once again, set the active back to 1 (<active>1</active> ) save changes then restart the server. All should be fixed. 




If you need help feel free to add me on discord and ill be happy to help. Discord: jamracked
