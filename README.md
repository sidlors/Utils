# Utils
Utilerias Para desarrollos

Plugins Para Eclipse Kepler
```xml
<?xml version="1.0" encoding="UTF-8"?>
<bookmarks>
   <site url="http://update.atlassian.com/atlassian-eclipse-plugin/e3.6" selected="true" name="Atlassian Jira conector"/>
   <site url="http://update.eclemma.org" selected="true" name="Cobertura"/>
   <site url="http://dl.google.com/eclipse/inst/codepro/latest/3.5" selected="true" name="CodePro Google"/>
   <site url="http://eclipse-color-theme.github.com/update" selected="true" name="com.github.eclipsecolortheme.updatesite"/>
   <site url="http://ecobertura.johoop.de/update" selected="true" name="ecobertura"/>
   <site url="http://download.jboss.org/jbosstools/updates/stable/kepler/" selected="true" name="JBoss Tools 4.1 - Core - Stable Release Update Site"/>
   <site url="http://download.jboss.org/jbosstools/targetplatforms/jbosstoolstarget/kepler/" selected="true" name="JBoss Tools Target Platform - Kepler"/>
   <site url="http://download.eclipse.org/releases/kepler" selected="true" name="Kepler"/>
   <site url="http://archive.eclipse.org/mylyn/drops/3.8.0/v20120612-0600" selected="true" name="Mylyn for Eclipse 3.6, 3.7 and 3.8"/>
   <site url="http://download.eclipse.org/mylyn/releases/kepler" selected="true" name="Mylyn for Eclipse Kepler"/>
   <site url="http://download.oracle.com/otn_software/oepe/kepler" selected="true" name="Oracle Eclipse Pack for Eclipse"/>
   <site url="http://download.eclipse.org/tools/gef/updates/releases" selected="true" name="org.eclipse.gef.repository"/>
   <site url="http://www.soapui.org/eclipse/update" selected="true" name="SOAPUI"/>
   <site url="http://download.eclipse.org/technology/subversive/2.0/update-site/" selected="true" name="Subversive Site"/>
   <site url="http://download.eclipse.org/eclipse/updates/4.3" selected="true" name="The Eclipse Project Updates"/>
   <site url="http://download.eclipse.org/webtools/repository/kepler" selected="true" name="The Eclipse Web Tools Platform (WTP) software repository"/>
   <site url="http://community.polarion.com/projects/subversive/download/eclipse/4.0/update-site/" selected="true" name="Update Site"/>
</bookmarks>
```

Templates 

```xml
<?xml version="1.0" encoding="UTF-8" standalone="no"?><templates><template autoinsert="true" context="javadoc" deleted="false" description="author name" enabled="true" id="org.eclipse.jdt.ui.templates.author" name="@author">@author ${user}</template><template autoinsert="true" context="javadoc" deleted="false" description="&lt;b&gt;&lt;/b&gt;" enabled="true" id="org.eclipse.jdt.ui.templates.b_tag" name="&lt;b&gt;">&lt;b&gt;${word_selection}${}&lt;/b&gt;${cursor}</template><template autoinsert="true" context="javadoc" deleted="false" description="&lt;code&gt;&lt;/code&gt;" enabled="true" id="org.eclipse.jdt.ui.templates.code_tag" name="&lt;code&gt;">&lt;code&gt;${word_selection}${}&lt;/code&gt;${cursor}</template><template autoinsert="true" context="javadoc" deleted="false" description="&lt;i&gt;&lt;/i&gt;" enabled="true" id="org.eclipse.jdt.ui.templates.i_tag" name="&lt;i&gt;">&lt;i&gt;${word_selection}${}&lt;/i&gt;${cursor}</template><template autoinsert="true" context="javadoc" deleted="false" description="&lt;pre&gt;&lt;/pre&gt;" enabled="true" id="org.eclipse.jdt.ui.templates.pre_tag" name="&lt;pre&gt;">&lt;pre&gt;${word_selection}${}&lt;/pre&gt;${cursor}</template><template autoinsert="true" context="javadoc" deleted="false" description="active task" enabled="true" id="org.eclipse.mylyn.ide.ui.template.activeTask" name="active_task">${activeTaskPrefix}${activeTaskKey}</template><template autoinsert="false" context="swt-statements" deleted="false" description="add a listener to a Widget " enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.addlistener" name="addlistener">${control:var(org.eclipse.swt.widgets.Widget)}.addListener(${type:link(
	SWT.Activate,
	SWT.Arm,
	SWT.Close,
	SWT.Collapse,
	SWT.Deactivate,
	SWT.DefaultSelection,
	SWT.Deiconify,
	SWT.Dispose,
	SWT.DragDetect,
	SWT.EraseItem,
	SWT.Expand,
	SWT.FocusIn,
	SWT.FocusOut,
	SWT.HardKeyDown,
	SWT.HardKeyUp,
	SWT.Help,
	SWT.Hide,
	SWT.Iconify,
	SWT.ImeComposition,
	SWT.KeyDown,
	SWT.KeyUp,
	SWT.MeasureItem,
	SWT.MenuDetect,
	SWT.Modify,
	SWT.MouseDoubleClick,
	SWT.MouseDown,
	SWT.MouseEnter,
	SWT.MouseExit,
	SWT.MouseHover,
	SWT.MouseMove,
	SWT.MouseUp,
	SWT.MouseWheel,
	SWT.Move,
	SWT.Paint,
	SWT.PaintItem,
	SWT.Resize,
	SWT.Selection,
	SWT.SetData,
	SWT.Settings,
	SWT.Show,
	SWT.Traverse,
	SWT.Verify)}, new ${listener:newType(org.eclipse.swt.widgets.Listener)}(){
	public void handleEvent(${event:newType(org.eclipse.swt.widgets.Event)} e) {
		${imp:import(org.eclipse.swt.SWT)}${cursor}				
	}
});</template><template autoinsert="true" context="java-members" deleted="false" description="tear down after test" enabled="true" name="after">@${afterType:newType(org.junit.After)}
public void tearDown() throws Exception {
    ${cursor}
}</template><template autoinsert="true" context="java-members" deleted="false" description="tear down after test class" enabled="true" name="afterclass">@${afterType:newType(org.junit.AfterClass)}
public void tearDownAfterClass() throws Exception {
    ${cursor}
}</template><template autoinsert="false" context="java-statements" deleted="false" description="add an element to an array" enabled="true" id="org.eclipse.jdt.ui.templates.arrayadd" name="arrayadd">${array_type}[] ${result:newName(array)} = new ${array_type}[${array}.length + 1];
System.arraycopy(${array}, 0, ${result}, 0, ${array}.length);
${result}[${array}.length]= ${var};</template><template autoinsert="false" context="java-statements" deleted="false" description="merge two arrays into one" enabled="true" id="org.eclipse.jdt.ui.templates.arraymerge" name="arraymerge">${array_type}[] ${result:newName(array1)} = new ${array_type}[${array1:array}.length + ${array}.length];
System.arraycopy(${array1}, 0, ${result}, 0, ${array1}.length);
System.arraycopy(${array}, 0, ${result}, ${array1}.length, ${array}.length);</template><template autoinsert="true" context="java-statements" deleted="false" description="assert that" enabled="true" name="assert">${matchersImport:importStatic('org.hamcrest.Matchers.*')}${assertThatImport:importStatic('org.junit.Assert.assertThat')}assertThat(${word_selection}${}, ${matcher:newType(org.hamcrest.Matchers)}.${cursor});</template><template autoinsert="false" context="swt-statements" deleted="false" description="new Browser" enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.browser" name="Browser">${browserType:newType(org.eclipse.swt.browser.Browser)} ${browser:newName(org.eclipse.swt.browser.Browser)}= new ${browserType}(${parent:var(org.eclipse.swt.widgets.Composite)}, ${style:link(SWT.NONE, SWT.MOZILLA)});
${browser}.setLayoutData(new ${gridDataType:newType(org.eclipse.swt.layout.GridData)}(SWT.${horizontal:link(FILL, BEGINNING, CENTER, END)}, SWT.${vertical:link(FILL, TOP, CENTER, BOTTOM)}, ${hex:link(true, false)}, ${vex:link(true, false)}));
${browser}.setUrl(${word_selection}${});
${imp:import(org.eclipse.swt.SWT)}${cursor}</template><template autoinsert="true" context="java-members" deleted="false" description="generate equals, hashCode and toString with builder" enabled="true" name="builder equals hashcode">${importEqualsBuilder:import(org.apache.commons.lang3.builder.EqualsBuilder)}@Override
public boolean equals(Object obj) {
	if (obj == null) { return false; }
	if (obj == this) { return true; }
	if (obj.getClass() != getClass()) { return false; }
	${type:enclosing_type} rhs = (${type}) obj;
	return new EqualsBuilder()
	.appendSuper(super.equals(obj))
	.append(this.${field1:field}, rhs.${field1})
	.append(this.${field2:field}, rhs.${field2})
	.append(this.${field3:field}, rhs.${field3})${cursor}
	.isEquals();
}
${importHashCodeBuilder:import(org.apache.commons.lang3.builder.HashCodeBuilder)}@Override
public int hashCode() {
	return new HashCodeBuilder(${17}, ${37})
	.append(${field1})
	.append(${field2})
	.append(${field3})
	.toHashCode();
}
${importToStringBuilder:import(org.apache.commons.lang3.builder.ToStringBuilder)}${importToStringStyle:import(org.apache.commons.lang3.builder.ToStringStyle)}@Override
public String toString() {
	return new ToStringBuilder(this, ToStringStyle.${DEFAULT_STYLE})
	.append("${field1}", ${field1})
	.append("${field2}", ${field2})
	.append("${field3}", ${field3})
	.toString();
}</template><template autoinsert="true" context="java-members" deleted="false" description="generate equals, hashCode and toString with builder by reflection" enabled="true" name="builder equals hashcode reflection">${importEqualsBuilder:import(org.apache.commons.lang3.builder.EqualsBuilder)}@Override
public boolean equals(Object obj) {
	return EqualsBuilder.reflectionEquals(this, obj);
}

${importHashCodeBuilder:import(org.apache.commons.lang3.builder.HashCodeBuilder)}@Override
public int hashCode() {
	return HashCodeBuilder.reflectionHashCode(${17}, ${37}, this);
}

${importToStringBuilder:import(org.apache.commons.lang3.builder.ToStringBuilder, org.apache.commons.lang3.builder.ToStringStyle)}@Override
public String toString() {
	return ToStringBuilder.reflectionToString(this, ToStringStyle.${DEFAULT_STYLE});
}
${cursor}</template><template autoinsert="false" context="swt-statements" deleted="false" description="new Button" enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.button" name="Button">${buttonType:newType(org.eclipse.swt.widgets.Button)} ${button:newName(org.eclipse.swt.widgets.Button)}= new ${buttonType}(${parent:var(org.eclipse.swt.widgets.Composite)}, ${style:link(SWT.PUSH, SWT.TOGGLE, SWT.RADIO, SWT.CHECK, SWT.FLAT)});
${button}.setLayoutData(new ${type:newType(org.eclipse.swt.layout.GridData)}(SWT.${horizontal:link(BEGINNING, CENTER, END, FILL)}, SWT.${vertical:link(CENTER, TOP, BOTTOM, FILL)}, ${hex:link(false, true)}, ${vex:link(false, true)}));
${button}.setText(${word_selection}${});
${imp:import(org.eclipse.swt.SWT)}${cursor}</template><template autoinsert="false" context="java-statements" deleted="false" description="dynamic cast" enabled="true" id="org.eclipse.jdt.ui.templates.cast" name="cast">${type} ${new_name} = (${type}) ${name};</template><template autoinsert="false" context="java-statements" deleted="false" description="catch block" enabled="true" id="org.eclipse.jdt.ui.templates.catch" name="catch">catch (${Exception} ${exception_variable_name}) {
	${cursor}// ${todo}: handle exception
}</template><template autoinsert="true" context="java" deleted="false" description="" enabled="true" name="channel">${:import(com.jalios.jcms.Channel)}&#13;
&#13;
private static final Channel channel = Channel.getChannel();</template><template autoinsert="true" context="java" deleted="false" description="channelListener sample implementation" enabled="true" name="channelListener">${:import(java.text.ParseException, org.apache.log4j.Logger, com.jalios.jcms.Channel, com.jalios.jcms.ChannelListener, com.jalios.jcms.plugin.Plugin, com.jalios.jcms.plugin.PluginComponent, com.jalios.jdring.AlarmEntry, com.jalios.jdring.AlarmListener, com.jalios.jdring.AlarmManager, com.jalios.jdring.PastDateException)}&#13;
&#13;
public class ${enclosing_type} extends ChannelListener implements PluginComponent {&#13;
&#13;
  /**&#13;
   * The Channel.&#13;
   */&#13;
  private static final Channel channel = Channel.getChannel();&#13;
&#13;
  /**&#13;
   * The logger.&#13;
   */&#13;
  private static final Logger logger = Logger.getLogger(${enclosing_type}.class);&#13;
&#13;
  @Override&#13;
  public void initAfterStoreLoad() {&#13;
    try {&#13;
&#13;
      // Alarm declaration sample code&#13;
      String schedule = channel.getProperty("jcmsplugin.myplugin.mycron");&#13;
      AlarmListener alarmListener = new MyAlarmListener();&#13;
      AlarmEntry alarmEntry = new AlarmEntry(schedule, alarmListener);&#13;
      AlarmManager alarmMgr = channel.getCommonAlarmManager();&#13;
      alarmMgr.addAlarm(alarmEntry);&#13;
&#13;
      ${cursor}&#13;
&#13;
    } catch (PastDateException ex) {&#13;
      logger.error(ex, ex);&#13;
    } catch (ParseException e) {&#13;
      logger.error(e, e);&#13;
    } &#13;
  }&#13;
&#13;
  @Override&#13;
  public boolean init(Plugin plugin) {&#13;
    return true;&#13;
  }&#13;
&#13;
  @Override&#13;
  public void handleFinalize() {&#13;
  }&#13;
&#13;
  @Override&#13;
  public void initBeforeStoreLoad() {&#13;
  }&#13;
}</template><template autoinsert="false" context="swt-statements" deleted="false" description="new Combo" enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.combo" name="Combo">${comboType:newType(org.eclipse.swt.widgets.Combo)} ${combo:newName(org.eclipse.swt.widgets.Combo)}= new ${comboType}(${parent:var(org.eclipse.swt.widgets.Composite)}, ${style:link(SWT.DROP_DOWN, 'SWT.DROP_DOWN | SWT.READ_ONLY')});
${combo}.setLayoutData(new ${gridDataType:newType(org.eclipse.swt.layout.GridData)}(SWT.${horizontal:link(FILL, BEGINNING, CENTER, END)}, SWT.${vertical:link(CENTER, TOP, BOTTOM, FILL)}, ${hex:link(true, false)}, ${vex:link(false, true)}));
${combo}.setItems(${word_selection}${});
${imp:import(org.eclipse.swt.SWT)}${cursor}</template><template autoinsert="false" context="swt-statements" deleted="false" description="new Composite with GridLayout" enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.gridcomposite" name="Composite">${compositeType:newType(org.eclipse.swt.widgets.Composite)} ${composite:newName(org.eclipse.swt.widgets.Composite)}= new ${compositeType}(${parent:var(org.eclipse.swt.widgets.Composite)}, ${style:link(SWT.NONE, SWT.BORDER)});
${composite}.setLayoutData(new ${gridDataType:newType(org.eclipse.swt.layout.GridData)}(SWT.${horizontal:link(FILL, BEGINNING, CENTER, END)}, SWT.${vertical:link(FILL, TOP, CENTER, BOTTOM)}, ${hex:link(true, false)}, ${vex:link(true, false)}));
${composite}.setLayout(new ${layoutType:newType(org.eclipse.swt.layout.GridLayout)}(${numberColumns:link(1, 2, 3, 4, 5)}, ${equalColumns:link(false, true)}));
${imp:import(org.eclipse.swt.SWT)}${cursor}</template><template autoinsert="false" context="swt-statements" deleted="false" description="new DateTime" enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.datetime" name="DateTime">${dateType:newType(org.eclipse.swt.widgets.DateTime)} ${dateTime:newName(org.eclipse.swt.widgets.DateTime)}= new ${dateType}(${parent:var(org.eclipse.swt.widgets.Composite)}, ${style:link('SWT.CALENDAR | SWT.SHORT', 'SWT.CALENDAR | SWT.MEDIUM', 'SWT.CALENDAR | SWT.LONG', 'SWT.TIME | SWT.SHORT', 'SWT.TIME | SWT.MEDIUM', 'SWT.TIME | SWT.LONG', 'SWT.DATE | SWT.SHORT', 'SWT.DATE | SWT.MEDIUM', 'SWT.DATE | SWT.LONG')});
${dateTime}.setLayoutData(new ${gridDataType:newType(org.eclipse.swt.layout.GridData)}(SWT.${horizontal:link(FILL, BEGINNING, CENTER, END)}, SWT.${vertical:link(FILL, TOP, CENTER, BOTTOM)}, ${hex:link(true, false)}, ${vex:link(true, false)}));
${imp:import(org.eclipse.swt.SWT)}${cursor}</template><template autoinsert="true" context="java" deleted="false" description="logger.debug()" enabled="true" name="debug">if (logger.isDebugEnabled()) {&#13;
  logger.debug("${cursor}");&#13;
}</template><template autoinsert="true" context="java" deleted="false" description="logger.debug(o)" enabled="true" name="debug">if (logger.isDebugEnabled()) {&#13;
  logger.debug("${word_selection} is ${cursor} : " + ${word_selection});&#13;
}</template><template autoinsert="false" context="java-statements" deleted="false" description="do while statement" enabled="true" id="org.eclipse.jdt.ui.templates.do" name="do">do {
	${line_selection}${cursor}
} while (${condition:var(boolean)});</template><template autoinsert="false" context="java-statements" deleted="false" description="else block" enabled="true" id="org.eclipse.jdt.ui.templates.else" name="else">else {
	${cursor}
}</template><template autoinsert="false" context="java-statements" deleted="false" description="else if block" enabled="true" id="org.eclipse.jdt.ui.templates.elseif" name="elseif">else if (${condition:var(boolean)}) {
	${cursor}
}</template><template autoinsert="false" context="swt-statements" deleted="false" description="execute a runnable in the UI thread" enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.execute" name="execute">${display:var(org.eclipse.swt.widgets.Display)}.${kind:link(syncExec, asyncExec)}(new ${runnable:newType(java.lang.Runnable)}(){
	public void run(){
		${cursor}
	}
});</template><template autoinsert="false" context="swt-statements" deleted="false" description="new ExpandBar" enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.expandbar" name="ExpandBar">${type:newType(org.eclipse.swt.widgets.ExpandBar)} ${bar:newName(org.eclipse.swt.widgets.ExpandBar)}= new ${type}(${parent:var(org.eclipse.swt.widgets.Composite)}, ${style:link(SWT.V_SCROLL, SWT.NONE)});
${bar}.setLayoutData(new ${gridDataType:newType(org.eclipse.swt.layout.GridData)}(SWT.${horizontal:link(FILL, BEGINNING, CENTER, END)}, SWT.${vertical:link(FILL, TOP, CENTER, BOTTOM)}, ${hex:link(true, false)}, ${vex:link(true, false)}));
${imp:import(org.eclipse.swt.SWT)}${cursor}</template><template autoinsert="false" context="swt-statements" deleted="false" description="new ExpandItem for an ExpandBar" enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.expanditem" name="ExpandItem">${type:newType(org.eclipse.swt.widgets.ExpandItem)} ${item:newName(org.eclipse.swt.widgets.ExpandItem)}= new ${type}(${parent:var(org.eclipse.swt.widgets.ExpandBar)}, SWT.NONE);
${item}.setText(${word_selection}${});
${imp:import(org.eclipse.swt.SWT)}${cursor}

${item}.setControl(${control});
${item}.setHeight(${control}.computeSize(SWT.DEFAULT, SWT.DEFAULT).y);</template><template autoinsert="false" context="java-statements" deleted="false" description="$FALL-THROUGH$ marker" enabled="true" id="org.eclipse.jdt.ui.templates.fall-through" name="fall-through">//$$FALL-THROUGH$$</template><template autoinsert="true" context="javadoc" deleted="false" description="&lt;code&gt;false&lt;/code&gt;" enabled="true" id="org.eclipse.jdt.ui.templates.code_tag_false" name="false">&lt;code&gt;false&lt;/code&gt;</template><template autoinsert="false" context="java-statements" deleted="false" description="iterate over array" enabled="true" id="org.eclipse.jdt.ui.templates.for_array" name="for">for (int ${index} = 0; ${index} &lt; ${array}.length; ${index}++) {
	${line_selection}${cursor}
}</template><template autoinsert="false" context="java-statements" deleted="false" description="iterate over array with temporary variable" enabled="true" id="org.eclipse.jdt.ui.templates.for_temp" name="for">for (int ${index} = 0; ${index} &lt; ${array}.length; ${index}++) {
	${array_type} ${array_element} = ${array}[${index}];
	${cursor}
}</template><template autoinsert="false" context="java-statements" deleted="false" description="iterate over collection" enabled="true" id="org.eclipse.jdt.ui.templates.for_collection" name="for">for (${iteratorType:newType(java.util.Iterator)} ${iterator} = ${collection}.iterator(); ${iterator}.hasNext(); ) {
	${type:elemType(collection)} ${name:newName(type)} = (${type}) ${iterator}.next();
	${cursor}
}</template><template autoinsert="true" context="java-statements" deleted="false" description="iterate over map" enabled="true" name="for">for (${iteratorType:newType(java.util.Map)}.Entry&lt;${argType0:argType(map, 0)}, ${argType1:argType(map, 1)}&gt; ${entry} : ${map:localVar(java.util.Map)}.entrySet()) {
	${argType0} key = ${entry}.getKey();
	${argType1} value = ${entry}.getValue();
	${cursor}
}
</template><template autoinsert="false" context="java-statements" deleted="false" description="iterate over an array or Iterable" enabled="true" id="org.eclipse.jdt.ui.templates.for_iterable" name="foreach">for (${iterable_type} ${iterable_element} : ${iterable}) {
	${cursor}
}</template><template autoinsert="false" context="swt-statements" deleted="false" description="new GridData for a Control" enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.griddata" name="GridData">${gridData:newType(org.eclipse.swt.layout.GridData)} ${layoutData:newName(org.eclipse.swt.layout.GridData)} = new ${gridData}(SWT.${horizontal:link(FILL, BEGINNING, CENTER, END)}, SWT.${vertical:link(FILL, TOP, CENTER, BOTTOM)}, ${hex:link(true, false)}, ${vex:link(false, true)});
${layoutData}.widthHint= ${width:link(SWT.DEFAULT)};
${layoutData}.heightHint= ${height:link(SWT.DEFAULT)};
${parent:var(org.eclipse.swt.widgets.Control)}.setLayoutData(${layoutData});
${imp:import(org.eclipse.swt.SWT)}${cursor}</template><template autoinsert="false" context="swt-statements" deleted="false" description="new GridLayout for a Composites" enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.gridlayout" name="GridLayout">${gridLayout:newType(org.eclipse.swt.layout.GridLayout)} ${layout:newName(org.eclipse.swt.layout.GridLayout)} = new ${gridLayout}(${columns:link(1, 2, 3, 4, 5)}, ${width:link(false, true)});
${layout}.marginWidth = ${marginW:link(5, 0)};
${layout}.marginHeight = ${marginH:link(5, 0)};
${layout}.verticalSpacing = ${vSpacing:link(0, 5)};
${layout}.horizontalSpacing = ${hSpacing:link(0, 5)};
${parent:var(org.eclipse.swt.widgets.Composite)}.setLayout(${layout});
${cursor}</template><template autoinsert="false" context="swt-statements" deleted="false" description="new Group with GridLayout" enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.group" name="Group">${groupType:newType(org.eclipse.swt.widgets.Group)} ${group:newName(org.eclipse.swt.widgets.Group)}= new ${groupType}(${parent:var(org.eclipse.swt.widgets.Composite)}, ${style:link(SWT.NONE, SWT.SHADOW_ETCHED_IN, SWT.SHADOW_ETCHED_OUT, SWT.SHADOW_IN, SWT.SHADOW_OUT, SWT.SHADOW_NONE)});
${group}.setLayoutData(new ${gridDataType:newType(org.eclipse.swt.layout.GridData)}(SWT.${horizontal:link(FILL, BEGINNING, CENTER, END)}, SWT.${vertical:link(FILL, TOP, CENTER, BOTTOM)}, ${hex:link(true, false)}, ${vex:link(false, true)}));
${group}.setLayout(new ${layoutType:newType(org.eclipse.swt.layout.GridLayout)}(${numberColumns:link(1, 2, 3, 4, 5)}, ${equalColumns:link(false, true)}));
${group}.setText(${word_selection}${});
${imp:import(org.eclipse.swt.SWT)}${cursor}</template><template autoinsert="false" context="java-statements" deleted="false" description="if statement" enabled="true" id="org.eclipse.jdt.ui.templates.if" name="if">if (${condition:var(boolean)}) {
	${line_selection}${cursor}
}</template><template autoinsert="false" context="java-statements" deleted="false" description="if else statement" enabled="true" id="org.eclipse.jdt.ui.templates.ifelse" name="ifelse">if (${condition:var(boolean)}) {
	${cursor}
} else {
	
}</template><template autoinsert="true" context="java-statements" deleted="false" description="if local var != null block" enabled="true" name="ifnotnull">if (${localVar} != null) {
	${cursor}
}</template><template autoinsert="true" context="java-statements" deleted="false" description="if local var == null block" enabled="true" name="ifnull">if (${localVar} == null) {
	${cursor}
}</template><template autoinsert="true" context="java-statements" deleted="false" description="throws IllegalArgumentException" enabled="true" name="illegalArg">${:import(com.jalios.util.Util)}&#13;
if (Util.isEmpty(${word_selection})) {&#13;
	throw new IllegalArgumentException("${word_selection} must not be null.${cursor}");&#13;
}</template><template autoinsert="false" context="swt-statements" deleted="false" description="new Image" enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.image" name="Image">${labelType:newType(org.eclipse.swt.widgets.Label)} ${image:newName(org.eclipse.swt.widgets.Label)}= new ${labelType}(${parent:var(org.eclipse.swt.widgets.Composite)}, ${style:link(SWT.NONE, SWT.BORDER)});
${image}.setLayoutData(new ${type:newType(org.eclipse.swt.layout.GridData)}(SWT.${horizontal:link(BEGINNING, CENTER, END, FILL)}, SWT.${vertical:link(CENTER, TOP, BOTTOM, FILL)}, ${hex:link(false, true)}, ${vex:link(false, true)}));
${image}.setImage(${word_selection}${});
${imp:import(org.eclipse.swt.SWT)}${cursor}</template><template autoinsert="false" context="java-statements" deleted="false" description="dynamic type test and cast" enabled="true" id="org.eclipse.jdt.ui.templates.instanceof" name="instanceof">if (${name:var} instanceof ${type}) {
	${type} ${new_name} = (${type})${name};
	${cursor}
}</template><template autoinsert="false" context="swt-statements" deleted="false" description="new Label" enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.label" name="Label">${labelType:newType(org.eclipse.swt.widgets.Label)} ${label:newName(org.eclipse.swt.widgets.Label)}= new ${labelType}(${parent:var(org.eclipse.swt.widgets.Composite)}, ${style:link(SWT.NONE, SWT.WRAP, 'SWT.SEPARATOR | SWT.HORIZONTAL', 'SWT.SEPARATOR | SWT.VERTICAL')});
${label}.setLayoutData(new ${type:newType(org.eclipse.swt.layout.GridData)}(SWT.${horizontal:link(BEGINNING, CENTER, END, FILL)}, SWT.${vertical:link(CENTER, TOP, BOTTOM, FILL)}, ${hex:link(false, true)}, ${vex:link(false, true)}));
${label}.setText(${word_selection}${});
${imp:import(org.eclipse.swt.SWT)}${cursor}</template><template autoinsert="false" context="java-statements" deleted="false" description="lazy creation" enabled="true" id="org.eclipse.jdt.ui.templates.lazy" name="lazy">if (${name:var} == null) {
	${name} = new ${type}(${arguments});
	${cursor}
}

return ${name};</template><template autoinsert="false" context="swt-statements" deleted="false" description="new Link" enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.link" name="Link">${linkType:newType(org.eclipse.swt.widgets.Link)} ${link:newName(org.eclipse.swt.widgets.Link)}= new ${linkType}(${parent:var(org.eclipse.swt.widgets.Composite)}, SWT.NONE);
${link}.setLayoutData(new ${type:newType(org.eclipse.swt.layout.GridData)}(SWT.${horizontal:link(BEGINNING, CENTER, END, FILL)}, SWT.${vertical:link(CENTER, TOP, BOTTOM, FILL)}, ${hex:link(false, true)}, ${vex:link(false, true)}));
${link}.setText(${word_selection}${});
${imp:import(org.eclipse.swt.SWT)}${cursor}</template><template autoinsert="false" context="swt-statements" deleted="false" description="new List" enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.list" name="List">${type:newType(org.eclipse.swt.widgets.List)} ${list:newName(org.eclipse.swt.widgets.List)}= new ${type}(${parent:var(org.eclipse.swt.widgets.Composite)}, ${style:link('SWT.MULTI | SWT.V_SCROLL | SWT.H_SCROLL', 'SWT.MULTI | SWT.V_SCROLL', SWT.MULTI, 'SWT.SINGLE | SWT.V_SCROLL | SWT.H_SCROLL', 'SWT.SINGLE | SWT.V_SCROLL', SWT.SINGLE)});
${list}.setLayoutData(new ${gridDataType:newType(org.eclipse.swt.layout.GridData)}(SWT.${horizontal:link(FILL, BEGINNING, CENTER, END)}, SWT.${vertical:link(FILL, TOP, CENTER, BOTTOM)}, ${hex:link(true, false)}, ${vex:link(true, false)}));
${list}.setItems(${word_selection}${});
${imp:import(org.eclipse.swt.SWT)}${cursor}</template><template autoinsert="true" context="java-statements" deleted="false" description="log message" enabled="true" name="log">${log:field(org.slf4j.Logger)}.${level:link(debug, info, warn, error)}("${msg}"${});
${cursor}</template><template autoinsert="true" context="java-statements" deleted="false" description="log debug message" enabled="true" name="logd">${log:field(org.slf4j.Logger)}.debug("${msg}"${});
${cursor}</template><template autoinsert="true" context="java-statements" deleted="false" description="log error message" enabled="true" name="loge">${log:field(org.slf4j.Logger)}.error("${msg}"${});
${cursor}</template><template autoinsert="true" context="java" deleted="false" description="" enabled="true" name="logger">${:import(org.apache.log4j.Logger)}&#13;
private static final Logger logger = Logger.getLogger(${enclosing_type}.class);&#13;
&#13;
&#13;
</template><template autoinsert="true" context="java-statements" deleted="false" description="log info message" enabled="true" name="logi">${log:field(org.slf4j.Logger)}.info("${msg}"${});
${cursor}</template><template autoinsert="true" context="java-statements" deleted="false" description="log warning message" enabled="true" name="logw">${log:field(org.slf4j.Logger)}.warn("${msg}"${});
${cursor}</template><template autoinsert="false" context="java-members" deleted="false" description="main method" enabled="true" id="org.eclipse.jdt.ui.templates.main" name="main">public static void main(String[] args) {
	${cursor}
}</template><template autoinsert="false" context="swt-statements" deleted="false" description="new top level Shell with event loop" enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.mainloop" name="mainloop">${displayType:newType(org.eclipse.swt.widgets.Display)} ${display:newName(org.eclipse.swt.widgets.Display)} = new ${displayType}();
${shellType:newType(org.eclipse.swt.widgets.Shell)} ${shell:newName(org.eclipse.swt.widgets.Shell)} = new ${shellType}(${display});
${shell}.setLayout(new ${layoutType:newType(org.eclipse.swt.layout.GridLayout)}(${numberColumns:link(1, 2, 3, 4, 5)}, ${equalColumns:link(false, true)}));

${cursor}

${shell}.pack();
${shell}.open();
while (!${shell}.isDisposed()) {
	if (!${display}.readAndDispatch ()) 
		${display}.sleep();
}
${display}.dispose();</template><template autoinsert="false" context="java" deleted="false" description="create new object" enabled="true" id="org.eclipse.jdt.ui.templates.new" name="new">${type} ${name} = new ${type}(${arguments});</template><template autoinsert="false" context="java" deleted="false" description="non-externalized string marker" enabled="true" id="org.eclipse.jdt.ui.templates.non-nls" name="nls">//$$NON-NLS-${N}$$</template><template autoinsert="true" context="javadoc" deleted="false" description="&lt;code&gt;null&lt;/code&gt;" enabled="true" id="org.eclipse.jdt.ui.templates.code_tag_null" name="null">&lt;code&gt;null&lt;/code&gt;</template><template autoinsert="false" context="java-members" deleted="false" description="private method" enabled="true" id="org.eclipse.jdt.ui.templates.private_method" name="private_method">private ${return_type} ${name}(${}) {
	${cursor}
}</template><template autoinsert="false" context="java-members" deleted="false" description="private static method" enabled="true" id="org.eclipse.jdt.ui.templates.private_static_method" name="private_static_method">private static ${return_type} ${name}(${}) {
	${cursor}
}</template><template autoinsert="false" context="java-members" deleted="false" description="protected method" enabled="true" id="org.eclipse.jdt.ui.templates.protected_method" name="protected_method">protected ${return_type} ${name}(${}) {
	${cursor}
}</template><template autoinsert="false" context="java-members" deleted="false" description="public method" enabled="true" id="org.eclipse.jdt.ui.templates.public_method" name="public_method">public ${return_type} ${name}(${}) {
	${cursor}
}</template><template autoinsert="false" context="java-members" deleted="false" description="public static method" enabled="true" id="org.eclipse.jdt.ui.templates.public_static_method" name="public_static_method">public static ${return_type} ${name}(${}) {
	${cursor}
}</template><template autoinsert="false" context="java" deleted="false" description="runnable" enabled="true" id="org.eclipse.jdt.ui.templates.runnable" name="runnable">new Runnable() {
	public void run() {
		${line_selection}
	}
}</template><template autoinsert="false" context="swt-statements" deleted="false" description="new SashForm" enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.sashform" name="SashForm">${type:newType(org.eclipse.swt.custom.SashForm)} ${sash:newName(org.eclipse.swt.custom.SashForm)}= new ${type}(${parent:var(org.eclipse.swt.widgets.Composite)}, ${style:link(SWT.HORIZONTAL, SWT.VERTICAL)});
${sash}.setLayoutData(new ${gridDataType:newType(org.eclipse.swt.layout.GridData)}(SWT.${horizontal:link(FILL, BEGINNING, CENTER, END)}, SWT.${vertical:link(FILL, TOP, CENTER, BOTTOM)}, ${hex:link(true, false)}, ${vex:link(true, false)}));
${imp:import(org.eclipse.swt.SWT)}${cursor}

${sash}.setWeights(new int[] {1, 1});</template><template autoinsert="false" context="swt-statements" deleted="false" description="new Scale" enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.scale" name="Scale">${scaleType:newType(org.eclipse.swt.widgets.Scale)} ${scale:newName(org.eclipse.swt.widgets.Scale)}= new ${scaleType}(${parent:var(org.eclipse.swt.widgets.Composite)}, ${style:link(SWT.HORIZONTAL, SWT.VERTICAL)});
${scale}.setLayoutData(new ${gridDataType:newType(org.eclipse.swt.layout.GridData)}(SWT.${horizontal:link(BEGINNING, FILL, CENTER, END)}, SWT.${vertical:link(CENTER, TOP, BOTTOM, FILL)}, ${hex:link(false, true)}, ${vex:link(false, true)}));
${scale}.setMaximum(${max:link(100)});
${scale}.setIncrement(${inc:link(5)});
${imp:import(org.eclipse.swt.SWT)}${cursor}</template><template autoinsert="false" context="swt-statements" deleted="false" description="new ScrolledComposite" enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.scrolledcomposite" name="ScrolledComposite">${compositeType:newType(org.eclipse.swt.custom.ScrolledComposite)} ${scrolled:newName(org.eclipse.swt.custom.ScrolledComposite)} = new ${compositeType}(${parent:var(org.eclipse.swt.widgets.Composite)}, ${style:link('SWT.H_SCROLL | SWT.V_SCROLL', SWT.H_SCROLL, SWT.V_SCROLL)});
${scrolled}.setLayoutData(new ${gridDataType:newType(org.eclipse.swt.layout.GridData)}(SWT.${horizontal:link(FILL, BEGINNING, CENTER, END)}, SWT.${vertical:link(FILL, TOP, CENTER, BOTTOM)}, ${hex:link(true, false)}, ${vex:link(true, false)}));
${scrolled}.setExpandVertical(${exV:link(false, true)});
${scrolled}.setExpandHorizontal(${exH:link(false, true)});
${imp:import(org.eclipse.swt.SWT)}${cursor}

${scrolled}.setContent(${content});
Point ${contentSize:newName(org.eclipse.swt.graphics.Point)} = ${content}.computeSize(SWT.DEFAULT, SWT.DEFAULT);
${content}.setSize(${contentSize});
${scrolled}.setMinSize(${contentSize});</template><template autoinsert="false" context="swt-statements" deleted="false" description="new Shell" enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.shell" name="Shell">${shellType:newType(org.eclipse.swt.widgets.Shell)} ${shell:newName(org.eclipse.swt.widgets.Shell)} = new ${shellType}(${parent:var(org.eclipse.swt.widgets.Shell)}, ${style:link('SWT.DIALOG_TRIM | SWT.PRIMARY_MODAL', 'SWT.DIALOG_TRIM | SWT.MODELESS', 'SWT.SHELL_TRIM | SWT.MODELESS', 'SWT.SHELL_TRIM | SWT.PRIMARY_MODAL')});
${shell}.setLayout(new ${layoutType:newType(org.eclipse.swt.layout.GridLayout)}(${numberColumns:link(1, 2, 3, 4, 5)}, ${equalColumns:link(false, true)}));

${imp:import(org.eclipse.swt.SWT)}${cursor}

${shell}.pack();
${shell}.open();</template><template autoinsert="true" context="java" deleted="false" description="" enabled="true" name="singleton">private static final ${enclosing_type} SINGLETON = new ${enclosing_type}();  &#13;
  &#13;
// --------------------------------------------------------  &#13;
// Singleton &amp; init  &#13;
// --------------------------------------------------------  &#13;
private ${enclosing_type}() {  &#13;
  init();  &#13;
}  &#13;
  &#13;
public static ${enclosing_type} getInstance() {  &#13;
  return SINGLETON;  &#13;
}  &#13;
  &#13;
private void init() {  &#13;
  // TODO Add init code here  &#13;
}  </template><template autoinsert="false" context="swt-statements" deleted="false" description="new Spinner" enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.spinner" name="Spinner">${spinnerType:newType(org.eclipse.swt.widgets.Spinner)} ${spinner:newName(org.eclipse.swt.widgets.Spinner)}= new ${spinnerType}(${parent:var(org.eclipse.swt.widgets.Composite)}, ${style:link(SWT.BORDER, 'SWT.WRAP | SWT.BORDER', 'SWT.READ_ONLY | SWT.BORDER', 'SWT.READ_ONLY | SWT.WRAP | SWT.BORDER', SWT.WRAP, SWT.READ_ONLY)});
${spinner}.setLayoutData(new ${gridDataType:newType(org.eclipse.swt.layout.GridData)}(SWT.${horizontal:link(BEGINNING, CENTER, END, FILL)}, SWT.${vertical:link(CENTER, TOP, BOTTOM, FILL)}, ${hex:link(false, true)}, ${vex:link(false, true)}));
${spinner}.setMaximum(${max:link(10)});
${spinner}.setIncrement(${inc:link(1)});
${imp:import(org.eclipse.swt.SWT)}${cursor}</template><template autoinsert="false" context="java-members" deleted="false" description="static final field" enabled="true" id="org.eclipse.jdt.ui.templates.static_final" name="static_final">${visibility:link('public ','protected ','','private ')}static final ${type:link(String,int)} ${NAME} = ${expr:link('""',0)};</template><template autoinsert="false" context="swt-statements" deleted="false" description="new StyledText " enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.styledtext" name="StyledText">${type:newType(org.eclipse.swt.custom.StyledText)} ${text:newName(org.eclipse.swt.custom.StyledText)}= new ${type}(${parent:var(org.eclipse.swt.widgets.Composite)}, ${style:link('SWT.V_SCROLL | SWT.H_SCROLL', 'SWT.V_SCROLL | SWT.H_SCROLL | SWT.READ_ONLY', 'SWT.WRAP | SWT.V_SCROLL', SWT.NONE, SWT.BORDER, SWT.FULL_SELECTION)});
${text}.setLayoutData(new ${gridDataType:newType(org.eclipse.swt.layout.GridData)}(SWT.${horizontal:link(FILL, BEGINNING, CENTER, END)}, SWT.${vertical:link(FILL, TOP, CENTER, BOTTOM)}, ${hex:link(true, false)}, ${vex:link(true, false)}));
${text}.setText(${word_selection}${});
${imp:import(org.eclipse.swt.SWT)}${cursor}</template><template autoinsert="false" context="swt-statements" deleted="false" description="new StyleRange for a StyledText" enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.stylerange" name="StyleRange">${type:newType(org.eclipse.swt.custom.StyleRange)} ${range:newName(org.eclipse.swt.custom.StyleRange)}= new ${type}();
${range}.start= ${start:link(0)};
${range}.length= ${length:link(0)};
${range}.foreground= ${fColor:link(null, 'Display.getDefault().getSystemColor(SWT.COLOR_BLACK)', 'Display.getDefault().getSystemColor(SWT.COLOR_WHITE)', 'Display.getDefault().getSystemColor(SWT.COLOR_RED)', 'Display.getDefault().getSystemColor(SWT.COLOR_BLUE)', 'Display.getDefault().getSystemColor(SWT.COLOR_GREEN)')};
${range}.background= ${bColor:link(null, 'Display.getDefault().getSystemColor(SWT.COLOR_BLACK)', 'Display.getDefault().getSystemColor(SWT.COLOR_WHITE)', 'Display.getDefault().getSystemColor(SWT.COLOR_RED)', 'Display.getDefault().getSystemColor(SWT.COLOR_BLUE)', 'Display.getDefault().getSystemColor(SWT.COLOR_GREEN)')};
${range}.fontStyle= ${fStyle:link(SWT.NORMAL, SWT.ITALIC, SWT.BOLD)};
${text:var(org.eclipse.swt.custom.StyledText)}.setStyleRange(${range});
${imp:import(org.eclipse.swt.SWT, org.eclipse.swt.widgets.Display)}${cursor}</template><template autoinsert="false" context="java-statements" deleted="false" description="switch case statement" enabled="true" id="org.eclipse.jdt.ui.templates.switch" name="switch">switch (${key}) {
	case ${value}:
		${cursor}
		break;

	default:
		break;
}</template><template autoinsert="false" context="java-statements" deleted="false" description="synchronized block" enabled="true" id="org.eclipse.jdt.ui.templates.synchronized" name="synchronized">synchronized (${mutex:var}) {
	${line_selection}
}</template><template autoinsert="true" context="java-statements" deleted="false" description="print to standard error" enabled="true" id="org.eclipse.jdt.ui.templates.syserr" name="syserr">System.err.println(${word_selection}${});${cursor}</template><template autoinsert="true" context="java-statements" deleted="false" description="print to standard out" enabled="true" id="org.eclipse.jdt.ui.templates.sysout" name="sysout">System.out.println(${word_selection}${});${cursor}</template><template autoinsert="true" context="java-statements" deleted="false" description="print current method to standard out" enabled="true" id="org.eclipse.jdt.ui.templates.systrace" name="systrace">System.out.println("${enclosing_type}.${enclosing_method}()");</template><template autoinsert="false" context="swt-statements" deleted="false" description="new TabFolder" enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.tabfolder" name="TabFolder">${type:newType(org.eclipse.swt.widgets.TabFolder)} ${folder:newName(org.eclipse.swt.widgets.TabFolder)}= new ${type}(${parent:var(org.eclipse.swt.widgets.Composite)}, ${style:link(SWT.TOP, SWT.BOTTOM)});
${folder}.setLayoutData(new ${gridDataType:newType(org.eclipse.swt.layout.GridData)}(SWT.${horizontal:link(FILL, BEGINNING, CENTER, END)}, SWT.${vertical:link(FILL, TOP, CENTER, BOTTOM)}, ${hex:link(true, false)}, ${vex:link(true, false)}));
${imp:import(org.eclipse.swt.SWT)}${cursor}</template><template autoinsert="false" context="swt-statements" deleted="false" description="new TabItem for a TabFolder" enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.tabitem" name="TabItem">${type:newType(org.eclipse.swt.widgets.TabItem)} ${item:newName(org.eclipse.swt.widgets.TabItem)}= new ${type}(${parent:var(org.eclipse.swt.widgets.TabFolder)}, SWT.NONE);
${item}.setText(${word_selection}${});
${imp:import(org.eclipse.swt.SWT)}${cursor}

${item}.setControl(${control});</template><template autoinsert="false" context="swt-statements" deleted="false" description="new Table" enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.table" name="Table">${type:newType(org.eclipse.swt.widgets.Table)} ${table:newName(org.eclipse.swt.widgets.Table)}= new ${type}(${parent:var(org.eclipse.swt.widgets.Composite)}, ${style:link('SWT.SINGLE | SWT.FULL_SELECTION', 'SWT.MULTI | SWT.FULL_SELECTION', SWT.CHECK, SWT.NONE, SWT.VIRTUAL)});
${table}.setLayoutData(new ${gridDataType:newType(org.eclipse.swt.layout.GridData)}(SWT.${horizontal:link(FILL, BEGINNING, CENTER, END)}, SWT.${vertical:link(FILL, TOP, CENTER, BOTTOM)}, ${hex:link(true, false)}, ${vex:link(true, false)}));
${table}.setLinesVisible(${line:link(true, false)});
${table}.setHeaderVisible(${header:link(true, false)});
${imp:import(org.eclipse.swt.SWT)}${cursor}

for (int ${index} = 0; ${index} &lt; ${table}.getColumnCount(); ${index}++) {
	${table}.getColumn(${index}).pack();
}</template><template autoinsert="false" context="swt-statements" deleted="false" description="new TableColumn for a Table " enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.tablecolumn" name="TableColumn">${type:newType(org.eclipse.swt.widgets.TableColumn)} ${column:newName(org.eclipse.swt.widgets.TableColumn)}= new ${type}(${parent:var(org.eclipse.swt.widgets.Table)}, ${style:link(SWT.LEAD, SWT.CENTER, SWT.TRAIL)});
${column}.setText(${word_selection}${});
${imp:import(org.eclipse.swt.SWT)}${cursor}</template><template autoinsert="false" context="swt-statements" deleted="false" description="new TableItem for a Table" enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.tableitem" name="TableItem">${type:newType(org.eclipse.swt.widgets.TableItem)} ${item:newName(org.eclipse.swt.widgets.TableItem)}= new ${type}(${parent:var(org.eclipse.swt.widgets.Table)}, SWT.NONE);
${item}.setText(${count:link(0, 1, 2, 3, 4, 5)}, ${word_selection}${});
${imp:import(org.eclipse.swt.SWT)}${cursor}</template><template autoinsert="false" context="java-members" deleted="false" description="test method" enabled="true" id="org.eclipse.jdt.ui.templates.test" name="test">public void test${name}() throws Exception {
	${cursor} 
}</template><template autoinsert="true" context="java-members" deleted="false" description="test method (JUnit 4)" enabled="true" id="org.eclipse.jdt.ui.templates.test_junit4" name="test">@${testType:newType(org.junit.Test)}
public void ${testName}() throws Exception {
	${assertImport:importStatic('org.junit.Assert.*')}${matchersImport:importStatic('org.hamcrest.Matchers.*')}${mockImport:importStatic('org.easymock.EasyMock.*')}${cursor}
}</template><template autoinsert="false" context="swt-statements" deleted="false" description="new Text" enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.text" name="Text">${type:newType(org.eclipse.swt.widgets.Text)} ${text:newName(org.eclipse.swt.widgets.Text)}= new ${type}(${parent:var(org.eclipse.swt.widgets.Composite)}, ${style:link('SWT.SINGLE | SWT.LEAD | SWT.BORDER', 'SWT.SINGLE | SWT.LEAD | SWT.READ_ONLY | SWT.BORDER', 'SWT.SINGLE | SWT.LEAD | SWT.PASSWORD | SWT.BORDER', 'SWT.MULTI | SWT.WRAP | SWT.V_SCROLL | SWT.BORDER', 'SWT.MULTI | SWT.H_SCROLL | SWT.V_SCROLL | SWT.BORDER')});
${text}.setLayoutData(new ${gridDataType:newType(org.eclipse.swt.layout.GridData)}(SWT.${horizontal:link(FILL, BEGINNING, CENTER, END)}, SWT.${vertical:link(CENTER, TOP, BOTTOM, FILL)}, ${hex:link(true, false)}, ${vex:link(false, true)}));
${text}.setText(${word_selection}${});
${imp:import(org.eclipse.swt.SWT)}${cursor}</template><template autoinsert="false" context="java" deleted="false" description="convert collection to array" enabled="true" id="org.eclipse.jdt.ui.templates.toarray" name="toarray">(${type:elemType(collection)}[]) ${collection}.toArray(new ${type}[${collection}.size()])</template><template autoinsert="false" context="swt-statements" deleted="false" description="new ToolBar" enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.toolbar" name="ToolBar">${type:newType(org.eclipse.swt.widgets.ToolBar)} ${bar:newName(org.eclipse.swt.widgets.ToolBar)}= new ${type}(${parent:var(org.eclipse.swt.widgets.Composite)}, ${style:link(SWT.FLAT, SWT.WRAP, SWT.RIGHT, SWT.HORIZONTAL, SWT.VERTICAL, SWT.SHADOW_OUT)});
${bar}.setLayoutData(new ${gridDataType:newType(org.eclipse.swt.layout.GridData)}(SWT.${horizontal:link(FILL, BEGINNING, CENTER, END)}, SWT.${vertical:link(FILL, TOP, CENTER, BOTTOM)}, ${hex:link(true, false)}, ${vex:link(true, false)}));
${imp:import(org.eclipse.swt.SWT)}${cursor}</template><template autoinsert="false" context="swt-statements" deleted="false" description="new ToolItem for a ToolBar" enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.toolitem" name="ToolItem">${type:newType(org.eclipse.swt.widgets.ToolItem)} ${item:newName(org.eclipse.swt.widgets.ToolItem)}= new ${type}(${parent:var(org.eclipse.swt.widgets.ToolBar)}, ${style:link(SWT.PUSH, SWT.CHECK, SWT.RADIO, SWT.SEPARATOR, SWT.DROP_DOWN)});
${item}.setText(${word_selection}${});
${imp:import(org.eclipse.swt.SWT)}${cursor}</template><template autoinsert="true" context="java" deleted="false" description="" enabled="true" name="trace">if (logger.isTraceEnabled()) {&#13;
  logger.trace("${cursor}");&#13;
}</template><template autoinsert="true" context="java" deleted="false" description="" enabled="true" name="trace">if (logger.isTraceEnabled()) {&#13;
  logger.trace("${cursor}");&#13;
}</template><template autoinsert="false" context="swt-statements" deleted="false" description="new Tree" enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.tree" name="Tree">${type:newType(org.eclipse.swt.widgets.Tree)} ${tree:newName(org.eclipse.swt.widgets.Tree)}= new ${type}(${parent:var(org.eclipse.swt.widgets.Composite)}, ${style:link('SWT.SINGLE | SWT.FULL_SELECTION', 'SWT.MULTI | SWT.FULL_SELECTION', SWT.CHECK, SWT.NONE, SWT.VIRTUAL)});
${tree}.setLayoutData(new ${gridDataType:newType(org.eclipse.swt.layout.GridData)}(SWT.${horizontal:link(FILL, BEGINNING, CENTER, END)}, SWT.${vertical:link(FILL, TOP, CENTER, BOTTOM)}, ${hex:link(true, false)}, ${vex:link(true, false)}));
${tree}.setLinesVisible(${line:link(true, false)});
${tree}.setHeaderVisible(${header:link(true, false)});
${imp:import(org.eclipse.swt.SWT)}${cursor}

for (int ${index} = 0; ${index} &lt; ${tree}.getColumnCount(); ${index}++) {
	${tree}.getColumn(${index}).pack();
}</template><template autoinsert="false" context="swt-statements" deleted="false" description="new TreeColumn for a Tree " enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.treecolumn" name="TreeColumn">${type:newType(org.eclipse.swt.widgets.TreeColumn)} ${column:newName(org.eclipse.swt.widgets.TreeColumn)}= new ${type}(${parent:var(org.eclipse.swt.widgets.Tree)}, ${style:link(SWT.LEAD, SWT.CENTER, SWT.TRAIL)});
${column}.setText(${word_selection}${});
${imp:import(org.eclipse.swt.SWT)}${cursor}</template><template autoinsert="false" context="swt-statements" deleted="false" description="new TreeItem for a Tree" enabled="true" id="org.eclipse.jdt.ui.text.codetemplates.swt.treeitem" name="TreeItem">${type:newType(org.eclipse.swt.widgets.TreeItem)} ${item:newName(org.eclipse.swt.widgets.TreeItem)}= new ${type}(${parent:var(org.eclipse.swt.widgets.Tree, org.eclipse.swt.widgets.TreeItem)}, SWT.NONE);
${item}.setText(${count:link(0, 1, 2, 3, 4, 5)}, ${word_selection}${});
${imp:import(org.eclipse.swt.SWT)}${cursor}</template><template autoinsert="true" context="javadoc" deleted="false" description="&lt;code&gt;true&lt;/code&gt;" enabled="true" id="org.eclipse.jdt.ui.templates.code_tag_true" name="true">&lt;code&gt;true&lt;/code&gt;</template><template autoinsert="false" context="java-statements" deleted="false" description="try catch block" enabled="true" id="org.eclipse.jdt.ui.templates.try" name="try">try {
	${line_selection}${cursor}
} catch (${Exception} ${exception_variable_name}) {
	// ${todo}: handle exception
}</template><template autoinsert="false" context="java-statements" deleted="false" description="iterate with enumeration" enabled="true" id="org.eclipse.jdt.ui.templates.while_enumeration" name="while">while (${en:var(java.util.Enumeration)}.hasMoreElements()) {
	${type:argType(en)} ${elem:newName(type)} = (${type}) ${en}.nextElement();
	${cursor}
}</template><template autoinsert="false" context="java-statements" deleted="false" description="iterate with iterator" enabled="true" id="org.eclipse.jdt.ui.templates.while_iterator" name="while">while (${it:var(java.util.Iterator)}.hasNext()) {
	${type:argType(it)} ${elem:newName(type)} = (${type}) ${it}.next();
	${cursor}
}</template><template autoinsert="false" context="java-statements" deleted="false" description="while loop with condition" enabled="true" id="org.eclipse.jdt.ui.templates.while_condition" name="while">while (${condition:var(boolean)}) {
	${line_selection}${cursor}
}</template></templates>
```

