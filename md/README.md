ZeroRealmWeaver/
├── ZeroRealmWeaver.slnx
├── README.md
│
└── ZeroRealmWeaver/
    ├── ZeroRealmWeaver.csproj
    ├── App.xaml
    ├── App.xaml.cs
    ├── AssemblyInfo.cs
    ├── MainWindow.xaml
    ├── MainWindow.xaml.cs
    │
    ├── Views/
    │   ├── OverviewPage.xaml
    │   ├── OverviewPage.xaml.cs
    │   ├── DevicePage.xaml
    │   ├── DevicePage.xaml.cs
    │   ├── ProductionPage.xaml
    │   ├── ProductionPage.xaml.cs
    │   ├── ResearchPage.xaml
    │   ├── ResearchPage.xaml.cs
    │   ├── MarketPage.xaml
    │   ├── MarketPage.xaml.cs
    │   ├── CanvasPage.xaml
    │   └── CanvasPage.xaml.cs
    │
    ├── ViewModels/
    │   ├── MainWindowViewModel.cs
    │   ├── OverviewPageViewModel.cs
    │   ├── DevicePageViewModel.cs
    │   ├── ProductionPageViewModel.cs
    │   ├── ResearchPageViewModel.cs
    │   ├── MarketPageViewModel.cs
    │   └── CanvasPageViewModel.cs
    │
    ├── Models/
    │   ├── GameState.cs
    │   ├── Devices/
    │   │   ├── Device.cs
    │   │   ├── DeviceType.cs
    │   │   ├── DeviceStatus.cs
    │   │   └── DeviceUpgradePath.cs
    │   ├── Materials/
    │   │   ├── Material.cs
    │   │   ├── MaterialTier.cs
    │   │   └── Recipe.cs
    │   ├── Research/
    │   │   ├── ResearchTree.cs
    │   │   └── ResearchNode.cs
    │   ├── Market/
    │   │   ├── Buyer.cs
    │   │   ├── Order.cs
    │   │   └── AICompetitor.cs
    │   └── Canvas/
    │       ├── GridPoint.cs
    │       ├── PlacedDevice.cs
    │       └── Connection.cs
    │
    ├── Services/
    │   ├── Interfaces/
    │   │   ├── IGameLoopService.cs
    │   │   ├── IDeviceService.cs
    │   │   ├── IProductionService.cs
    │   │   ├── IResearchService.cs
    │   │   ├── IMarketService.cs
    │   │   ├── ICanvasService.cs
    │   │   └── ISaveLoadService.cs
    │   ├── GameLoopService.cs
    │   ├── DeviceService.cs
    │   ├── ProductionService.cs
    │   ├── ResearchService.cs
    │   ├── MarketService.cs
    │   ├── CanvasService.cs
    │   └── SaveLoadService.cs
    │
    ├── Behaviors/
    │   └── DragDropBehavior.cs
    │
    ├── Converters/
    │   ├── StatusToColorConverter.cs
    │   ├── TierToIconConverter.cs
    │   └── BoolToVisibilityConverter.cs
    │
    ├── Helpers/
    │   ├── MathHelper.cs
    │   └── JsonHelper.cs
    │
    └── Styles/
        └── GlobalStyles.xaml