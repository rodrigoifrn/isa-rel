# Comando adduser - criar usuario já com a pasta Home, shell e pré-configuração (recomendado para usuários básicos)

adduser -help
adduser [--uid id] [--firstuid id] [--lastuid id]
        [--gid id] [--firstgid id] [--lastgid id] [--ingroup group]
        [--add-extra-groups] [--encrypt-home] [--shell shell]
        [--comment comment] [--home dir] [--no-create-home]
        [--allow-all-names] [--allow-bad-names]
        [--disabled-password] [--disabled-login]
        [--conf file] [--extrausers] [--quiet] [--verbose] [--debug]
        user
    Add a normal user

adduser --system
        [--uid id] [--group] [--ingroup group] [--gid id]
        [--shell shell] [--comment comment] [--home dir] [--no-create-home]
        [--conf file] [--extrausers] [--quiet] [--verbose] [--debug]
        user
   Add a system user

adduser --group
        [--gid ID] [--firstgid id] [--lastgid id]
        [--conf file] [--extrausers] [--quiet] [--verbose] [--debug]
        group
addgroup
        [--gid ID] [--firstgid id] [--lastgid id]
        [--conf file] [--extrausers] [--quiet] [--verbose] [--debug]
        group
   Add a user group

addgroup --system
        [--gid id]
        [--conf file] [--extrausers] [--quiet] [--verbose] [--debug]
        group
   Add a system group

adduser [--extrausers] USER GROUP
   Add an existing user to an existing group
