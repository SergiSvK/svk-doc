# 🤖 Configurar el bot


## ¿Cómo puedo configurar mi bot?
Para evitar que otros usuarios puedan ver la configuración del bot.

<warning title="Permisos necesarios" >
    <list>
        <li> Se necesita permisos de <strong>Administrador</strong></li>
        <li> <strong>Solo</strong> el usuario que a ejecutado el comando puede usar el comando </li>
    </list>
</warning>

<procedure title="📝 Configurar el bot" id="configurar-el-bot">
    <step>
        <p>
            Escribe el comando <code>/config</code> en el canal de texto que desees.
        </p>
    </step>
    <step>
        <p>
            Se abrirá una ventana con las opciones de configuración del bot.
        </p>
        <img src="config_command.png" alt="completion suggestions for procedure" border-effect="line"/>
    </step>
    <step>
        <p>
            Selecciona la opción que desees.
        </p>
        <tabs>
            <tab title="Tipo de licencia">
                <p>
                    Puedes ver el tipo de licencia que tienes activa en tu servidor. Para ver las ventajas de cada licencia,
                    puedes verlas en la sección <a href="Default-topic.md#selecciona-tu-plan">🏷️ Selecciona tu plan</a>.
                </p>
            </tab>
            <tab title="Channels Config">
                <p>
                    En esta sección puedes configurar las funciones de los canales de texto.
                </p>
                <deflist collapsible="true">
                    <def title="Explicación canales" default-state="collapsed">
                        <table>
                            <tr>
                                <th>Tipo</th>
                                <th>Función</th>
                                <th>Selección</th>
                            </tr>
                            <tr>
                                <td>Spam</td>
                                <td>Alertas de spam</td>
                                <td>Un Canal</td>
                            </tr>
                            <tr>
                                <td>Report</td>
                                <td>Alertas de reportes de Usuarios</td>
                                <td>Un Canal</td>
                            </tr>
                            <tr>
                                <td>Welcome</td>
                                <td> En desarrollo</td>
                                <td>Un Canal</td>
                            </tr>
                            <tr>
                                <td>Logs</td>
                                <td>Registro del servidor</td>
                                <td>Un Canal</td>
                            </tr>
                            <tr>
                                <td>Ignore</td>
                                <td>Canales ignorados por el bot</td>
                                <td>Selección multiple</td>
                            </tr>
                        </table>
                    </def>
                    <def title="Imagen del menú" default-state="collapsed">
                        <img src="config_channels.png" alt="completion suggestions for procedure" border-effect="line"/>
                    </def>
                </deflist>
            </tab>
            <tab title="By Pass">
                <p>
                    El sistema de <code>bypass</code> permite saltar las restricciones de los comandos de %product% 
                    para algunos usuarios. Hay dos formas atraves de:
                </p>
                <deflist collapsible="true">
                    <def title="ByPass por Usuario" default-state="collapsed">
                        <list>
                            <li> Añadir: <code>/bypass add [UUID o @usuario]</code> </li>
                            <li> Eliminar: <code>/bypass remove [UUID o @usuario]</code> </li>
                        </list>
                        <warning title="Permisos necesarios" >
                            <list>
                                <li> Se necesita permisos de <strong>Administrador</strong> o de 
                                    <strong>Expulsión</strong>
                                </li>
                            </list>
                        </warning>
                    </def>
                    <def title="ByPass por Roles" default-state="collapsed">
                        <p>
                            En el <strong>menu desplegable</strong>, selecciona los roles que quieres que tengan bypass. Puedes seleccionar
                            varios roles. <br> Tienes varias opciones extras: <code>All Page</code> y <code>Clear Page</code>
                        </p>
                        <note>
                            <p>
                                En el caso de tengas muchos roles y no veas el rol que quieres seleccionar, puedes usar el buscador.
                                El buscador tiene dos botones de <code>previus</code> y <code>next</code> para ver los otros roles.
                            </p>
                        </note>
                        <img src="config_bypass.png" border-effect="line" alt="Imagen de bypass configuracion"/>
                    </def>
                </deflist>
            </tab>
        </tabs>
    </step>
</procedure>


<procedure title="📎Clip tutorial" collapsible="true" preview-src="config_channels.png" id="clip-tutorial">
    <p>
        🎯 El video esta en español, pero se entiende perfectamente. Empiza en el minuto <code>7:13</code>
    </p>
    <video src="https://youtu.be/_JfdvJ4hD84?si=nPxBluxm-TemPwOQ&t=433"/>
</procedure>



