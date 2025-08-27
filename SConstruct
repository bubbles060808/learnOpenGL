env = Environment(tools = ['mingw'])

env['ENV']['PATH'] = ['C:/bubbles/TDM-GCC-64/bin']

env.Append(CPPPATH = ['./include'])
env.Append(LIBPATH = ['./lib'])

# env.Append(LIBS = ['glfw3', 'opengl32', 'kernel32', 'user32', 'gdi32', 'winspool', 'shell32', 'ole32', 'oleaut32', 'uuid', 'comdlg32', 'advapi32'])
env.Append(LIBS = ['glfw3', 'gdi32'])

# env.Object('glad.c')
env.Program('learn', ['main.cpp', 'glad.c'])
