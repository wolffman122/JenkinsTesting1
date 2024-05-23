node {
    stage 'Checkout'
        echo 'Before checkout'
        checkout scm
        echo 'After checkout'

    state 'Build'
        bat ""${tool Build Tools 2022}\\msbuild" ConsoleApplication1\ConsoleApplication1.sln /p:Configuration=Release /p:Platform=x64 /p:ProductVersioin=1.0.0.1"
}